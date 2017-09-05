# Docker Ontology

This is an ontology that decribes the docker ecosystem. For the vocabulary that describes docker-compose please see LINK HERE.

![alt-text](https://raw.githubusercontent.com/langens-jonathan/diagrams/master/DockerVocab.png "Docker Vocabulary")

## Prefixes
* docker: `<https://w3.org/ns/bde/docker#>`
* nie: `<http://www.semanticdesktop.org/ontologies/2007/01/19/nie#>`
* crm: `<http://www.cidoc-crm.org/cidoc-crm/>`
* dct: `<http://purl.org/dc/terms/>`
* rdf: `<http://www.w3.org/1999/02/22-rdf-syntax-ns#>`

## Classes
* [Acquisition] (#Acquisition)
* [Container] (#Container)
* [ContainerVolume] (#ContainerVolume)
* [Env] (#Env)
* [HostMapping] (#HostMapping)
* [Image] (#Image)
* [LogDefinition] (#LogDefinition)
* [PortMapping] (#PortMapping)
* [TaggedImage] (#TaggedImage)
* [Volume] (#Volume)

## Properties

* [containerPath] (#containerPath)
* [createdAt] (#createdAt)
* [date] (#date)
* [format] (#format)
* [hostPath] (#hostPath)
* [key] (#key)
* [mode] (#mode)
* [modifiedAt] (#modifiedAt)
* [name] (#name)
* [protocol] (#protocol)
* [random] (#random)
* [readOnly] (#readOnly)
* [registry] (#registry)
* [runCommand] (#runCommand)
* [sha] (#sha)
* [source] (#source)
* [sourcePort] (#sourcePort)
* [tag] (#tag)
* [target] (#target)
* [targetIP] (#targetIP)
* [userNSRemap] (#userNSRemap)
* [value] (#value)
* [workDir] (#workDir)

# Classes

## Acquisition <a name="Acquisition"> </a>

#### Description
An acquisition represents a source from which a docker image (docker:TaggedImage) was built or pulled. It can be build locally in which case there is very little control as to the source. But it can also just be pulled from a registry such as hub.docker.com. Neither case guarantees that the image can be obtained again.

#### Equivalent
none

#### Properties
* docker:source
* docker:name
* docker:date

#### Relations

##### Domain of
[docker:date](#date)
[docker:name](#name)
[docker:source](#source)

##### Range of 

#### Example
```
<docker:Acquisition rdf:ID="acq">
  <docker:source>remote-registry</docker:source>
  <docker:name>hub.docker.com</docker:name>
  <docker:date>09-01-2017</docker:date>
</docker:Acquisition>
```

---

## Container <a name="Container"> </a>

#### Description
A docker container, either running or stopped. Containers are a way to package software in a format that can run isolated on a shared operating system. Unlike VMs, containers do not bundle a full operating system - only libraries and settings required to make the software work are needed. This makes for efficient, lightweight, self-contained systems and guarantees that software will always run the same, regardless of where it’s deployed.

#### Equivalent
none

#### Properties
* docker:name
* docker:runCommand
* docker:mode
* docker:userNSRemap

#### Relations

##### Domain of
[docker:mode](#mode)
[docker:name](#name)
[docker:runCommand](#runCommand)
[docker:userNSRemap](#userNSRemap)

##### Range of 

#### Example
```
<docker:Container rdf:ID="container">
  <docker:name>exampleproject_db_1</docker:source>
  <docker:runCommand>bash startup.sh</docker:runCommand>
  <docker:mode>global</docker:mode>
</docker:Container>
```

---

## ContainerVolume <a name="ContainerVolume"> </a>

#### Description
A mounted volume on a certain path in the container.

#### Equivalent
none

#### Properties
* docker:containerPath

#### Relations

##### Domain of
[docker:containerPath](#containerPath)
[docker:readOnly](#readOnly)

##### Range of 

#### Example
```
<docker:ContainerVolume rdf:ID="cvol">
  <docker:containerPath>/app</docker:containerPath>
</docker:ContainerVolume>
```

---

## Env <a name="Env"> </a>

#### Description
An environment variable, basically this is just key-value pair.

#### Equivalent
none

#### Properties
* docker:key
* docker:value

#### Relations

##### Domain of
[docker:key](#key)
[docker:value](#value)

##### Range of 

#### Example
```
<docker:Env rdf:ID="env">
  <docker:key>DEFAULT_QUERY_TIMEOUT</docker:key>
  <docker:value>10000</docker:value>
</docker:Env>
```

---

## HostMapping <a name="HostMapping"> </a>

#### Description
An external container can be mapped to this container through the use of links in docker terminology.

#### Equivalent
none

#### Properties
* docker:hostName
* docker:targetIP
* docker:targetContainer

#### Relations

##### Domain of
[targetIP](#targetIP)

##### Range of 

#### Example
```
<docker:HostMapping rdf:ID="map">
  <docker:hostName>db</docker:source>
  <docker:targetIP>"172.19.0.2"</docker:targetIP>
  <docker:targetContainer>db</docker:targetContainer>
</docker:HostMapping>
```

---

## Image <a name="Image"> </a>

#### Description
A docker image, not to be confused with a [tagged docker image] (#TaggedImage) (all images are assumed to have a tag).

#### Equivalent
none

#### Properties
* docker:name
* docker:registry

#### Relations

##### Domain of
[docker:name](#name)
[docker:registry](#registry)

##### Range of 
[docker:from](#from)

#### Example
```
<docker:Image rdf:ID="ubuntu">
  <docker:name>ubuntu</docker:name>
  <docker:registry>hub.docker.com</docker:registry>
</docker:Image>
```

---

## LogDefinition <a name="LogDefinition"> </a>

#### Description
Describes the format and properties of a given log. The idea is that effective log formats will subclass this log format. The most used docker log formats are: syslog and JSONLog.

#### Equivalent
none

#### Properties
* docker:format

#### Relations

##### Domain of
[format](#format)

##### Range of 

#### Example
```
<docker:LogFormat rdf:ID="lfmt">
  <docker:format>syslog</docker:format>
</docker:LogFormat>
```

---

## PortMapping <a name="PortMapping"> </a>

#### Description
Describes how the owning container's ports are mapped to the host's ports.

#### Equivalent
none

#### Properties
* docker:source
* docker:target
* docker:protocol
* docker:random

#### Relations

##### Domain of
[docker:protocol](#protocol)
[docker:random](#random)
[docker:sourcePort](#sourcePort)

##### Range of 

#### Example
```
<docker:PortMapping rdf:ID="prt">
  <docker:source>3000</docker:source>
  <docker:target>80</docker:target>
</docker:PortMapping>
```

---

## TaggedImage <a name="TaggedImage"> </a>

#### Description
A docker specific build for a docker image, for instance ubuntu:14.04. For the docker daemon this image is identified by the name and the tag. However the sha is locally considered to be equivalent but I can rebuild a name:tag and end up with a different sha.

#### Equivalent
none

#### Properties
* docker:tag
* docker:sha
* docker:createdAt
* docker:modifiedAt

#### Relations

##### Domain of
[docker:createdAt](#createdAt)
[docker:from](#from)
[docker:modifiedAt](#modifiedAt)
[docker:runCommand](#runCommand)
[docker:sha](#sha)
[docker:tag](#tag)
[docker:workDir](#workDir)

##### Range of 
[docker:from](#from)

#### Example
```
<docker:TaggedImage rdf:ID="tim">
  <docker:tag>14.04</docker:tag>
  <docker:sha>7822509e8343</docker:sha>
  <docker:createdAt>09-01-2017</docker:createdAt>
  <docker:modifiedAt>09-01-2017</docker:modifiedAt>
</docker:TaggedImage>
```

---

## Volume <a name="Volume"> </a>

#### Description
A mountable point on the host machine machine, this can be read-only.

#### Equivalent
none

#### Properties
* docker:hostPath
* docker:readOnly

#### Relations

##### Domain of
[docker:hostPath] (#hostPath)

##### Range of 

#### Example
```
<docker:Volume rdf:ID="vol">
  <docker:hostPath>/home/user/projects/example-app</docker:hostPath>
</docker:Volume>
```

---

# Properties

## containerPath <a name="containerPath"> </a>
The path inside the container. This is used to identify where a specific volume is mounted.

### rdfs:subClassOf
docker:containerPath rdfs:subClassOf nie:url

#### Domain
[ContainerVolume](#ContainerVolume)

#### Range
literal (string)

#### Examples
```
```

---

## createdAt <a name="createdAt"> </a>
The date at which something, an image in a registry in this case, was created. 

### rdfs:subClassOf
docker:containerPath rdfs:subClassOf dcterms:created

#### Domain
[TaggedImage](#TaggedImage)

#### Range
literal (xsd:date)

#### Examples
```
```

## date <a name="date"> </a>
The date at which an image was acquired by the described registry. For the local registry this would be the moment of build or pulling. This information can be necessary because you might rebuild an image with the same tag and this is also not prohibited by registries such as hub.docker.com.

#### Domain
[Acquisition](#Acquisition)

#### Range
literal (xsd:date)

#### Examples
```
```

---

## format <a name="format"> </a>
The format in which logs are written (most commonly this is syslog).

### rdfs:subClassOf
docker:format rdfs:subClassOf [dct:format](http://dublincore.org/documents/dcmi-terms/#elements-format)

#### Domain
[LogDefinition] (#LogDefinition)

#### Range
literal (string)

#### Examples
```
```

---

## from <a name=from"> </a>
The Image or TaggedImageof which a docker TaggedImage is an extension

#### Domain
[TaggedImage](#TaggedImage)

#### Range
[Image](#Image)
[TaggedImage](#TaggedImage)

#### Examples
```
```

---

## hostPath <a name="hostPath"> </a>
The path where a volume resides on the host machine.

#### Domain
[Volume](#Volume)

#### Range
literal (string)

#### Examples
```
```

---

## key <a name="key"> </a>
The key that a certain environment variable has.

### rdfs:subClassOf
docker:key rdfs:subClassOf [dct:title] (http://dublincore.org/documents/dcmi-terms/#title)

#### Domain
[Env](#Env)

#### Range
literal (string)

#### Examples
```
```

---

## mode <a name="mode"> </a>
The mode in which the container is running.

#### Domain
[Container](#Container)

#### Range

#### Examples
```
```

---

## modifiedAt <a name="modifiedAt"> </a>
The date at which a taggedImage has been modified. This differentiates from the creation as it can be build (created) on a server and then copied.

### rdfs:subClassOf
docker:modifiedAt rdfs:subClassOf [dct:modified](http://dublincore.org/documents/dcmi-terms/#terms-modified)

#### Domain
[Container](#Container)

#### Range

#### Examples
```
```

---

## name <a name="name"> </a>
The name of an image (on disk or on the registry from which it was obtained) or a container.

### rdfs:subClassOf
docker:image rdfs:subClassOf [dct:title](http://dublincore.org/documents/dcmi-terms/#title)

#### Domain
[Acquisition] (#Acquisition)
[Container] (#Container)
[Image] (#Image)

#### Range

#### Examples
```
```

---

## protocol <a name="protocol"> </a>
The protocol that is offered on a certain port mapping for a docker container or image.

#### Domain
[PortMapping](#PortMapping)

#### Range
literal (string)

#### Examples
```
```

---

## random <a name="random"> </a>
A flag that states that the host port mapping was done randomly. This can for exampmle happen when using the EXPOSED keyword in a Dockerfile.

#### Default
If not set the value of this flag is assumed to be false.

#### Domain
[PortMapping](#PortMapping)

#### Range
literal (boolean)

#### Examples
```
```

---

## readOnly <a name="readOnly"> </a>
A flag that indicates that the Volume on which this property was set is read only.

#### Default
If not set the value of this flag is assumed to be false.

#### Domain
[Volume](#Volume)

#### Range

#### Examples
```
```

---

## registry <a name="registry"> </a>
The location of the registry where this image is residing. This will be "local" for images that are stored locally (so for any image that is or will be run). The Acquisition object also has this relation to indicate from which registry the image was obtained.

#### rdfs:subClassOf
[docker:registry](#registry) rdfs:subClassOf [docker:source](#source)

#### Domain
[Image](#Image)

#### Range
literal (string)

#### Examples
```
```

---

## runCommand <a name="runCommand"> </a>
The command that is executed when the docker has been started.

#### Domain
[Container](#Container)
[TaggedImage](#TaggedImage)

#### Range
literal (string)

#### Examples
```
```

---

## sha <a name="sha"> </a>
The sha of a certain taggedImage.

#### Domain
[TaggedImage](#TaggedImage)

#### Range

#### Examples
```
```

---

## source <a name="source"> </a>
The source from which a docker image was obtained, this can be a registry but it can also be just a folder in which 
```
docker build -t <tag> .
```
was run.

#### rdfs:subClassOf
[docker:source](#source) rdfs:subClassOf [dct:source](http://dublincore.org/usage/terms/history/#sourceT-001)

#### rdfs:superClassOf
[docker:source](#source) rdfs:superClassOf [docker:registry](#registry)

#### Domain
[Acquisition](#Acquisition)

#### Range
literal (string)

#### Examples
```
```

---

## sourcePort <a name="sourcePort"> </a>
The port that is being exposed on a docker.

#### Domain
[PortMapping](#PortMapping)

#### Range
literal (number)

#### Examples
```
```

---

## tag <a name="tag"> </a>
The tag by which a 'version' of a docker image is known in a registry. (Ie. the docker image 'ubuntu' has tag '14:04' on the registry 'hub.docker.com' and this corresponds to the image 'ubuntu' with tag 'latest' on 'local'. The relation between hub.docker.com and local should in this case be made explicit through the Acquisition relation). 

#### Domain
[TaggedImage](#TaggedImage)

#### Range
literal (string)

#### Examples
```
```

---

## target <a name="target"> </a>
The target of a PortMapping is the host port on which a docker port is mapped.

#### Domain
[PortMapping](#PortMapping)

#### Range
literal (number)

#### Examples
```
```

---

## targetIP <a name="targetIP"> </a>
The IP of the docker to which a HostMapping is directed.

#### Domain
[HostMapping](#HostMapping)

#### Range
literal (string)

#### Examples
```
```

---

## userNSRemap <a name="userNSRemap"> </a>
The namespace remapping that is done for the container.

#### Domain
[Container](#Container)

#### Range
literal (string)

#### Examples
```
```

---

## value <a name="value"> </a>
The value of an environment variable.

#### rdfs:subClassOf
[docker:value](#value) rdfs:subClassOf [rdf:value](https://www.w3.org/TR/rdf-schema/#ch_value)

#### Domain
[Env](#Env)

#### Range
literal (string)

#### Examples
```
```

---

## workDir <a name="workDir"> </a>
The directory in which a certain image will boot.

#### Domain
[TaggedImage](#TaggedImage)

#### Range
literal (string)

#### Examples
```
```

---





