# Docker-Compose Ontology

This ontology describes how a docker-compose file relates to images and how it manages [docker containers](https://git.tenforce.com/Jonathan.Langens/vocabs/blob/master/docker.md) which are instantiations of thoses images.

![alt-text](https://raw.githubusercontent.com/langens-jonathan/diagrams/master/DockerComposeVocab.png, "Docker-Compose Vocabulary")

## Prefixes
* drc: `<https://w3.org/ns/bde/docker-compose#>`
* docker: `<https://w3.org/ns/bde/docker#>`

## Classes
* [DockerComposeFile](#DockerComposeFile)
* [Service](#Service)

## Properties

# Classes

<a name="DockerComposeFile"> </a>
## DockerComposeFile
#### Description
A Compose File is a file written with a specific docker-compose version in mind, expressed in YAML that describes a composition of dockers and how they relate to each other.

#### Equivalent
none

#### Properties
| Predicate                                                       | rdfs:subClassOf | Docker Inspect Value   | Type           | Arity |
| :---:                                                           | :---:           | :---:                  | :---:          | :---: |
| [docker](#docker):[blkioWeight](#blkioWeight)                   |                 | "BlkioWeight"          | literal:number |       |
| [docker](#docker):[blkioWeightDevice](#blkioWeightDevice)       |                 | "BlkioWeightDevice"    | literal:string |       |
| [docker](#docker):[blkioDeviceReadBps](#blkioDeviceReadBps)     |                 | "BlkioDeviceReadBps"   | literal:string |       |
| [docker](#docker):[blkioDeviceWriteBps](#blkioDeviceWriteBps)   |                 | "BlkioDeviceWriteBps"  | literal:string |       |
| [docker](#docker):[blkioDeviceReadIOps](#blkioDeviceReadIOps)   |                 | "BlkioDeviceReadIOps"  | literal:string |       |
| [docker](#docker):[blkioDeviceWriteIOps](#blkioDeviceWriteIOps) |                 | "BlkioDeviceWriteIOps" | literal:string |       |
| [dco](#dco):                                                    |                 |                        |                |       |

#### Relations

##### Domain of
[docker:hasBlockIO](#docker:hasBlockIO)

##### Range of 

#### Example
```
```

---


## DockerComposeFile <a name="DockerComposeFile"> </a>

### Definition
A Compose File is a file written with a specific docker-compose version in mind, expressed in YAML that describes a composition of dockers and how they relate to each other.

### Equivalent
none

### Properties
* drc:version
* drc:logDefinition

### Relations

### Domain of

### Range of

### Example
```
<drc:ComposeFile rdf:ID="drc">
  <drc:verion>2.0</drc:version>
</drc:ComposeFile>
```

---

## ContainerDefinition <a name="ContainerDefinition"> </a>

### Definition
Describes a container within the context of a docker-compose.yml file. This generally is one top level block in the YML.

### Equivalent
none

### Properties
* drc:name

### Domain of

### Range of

### Example
```
<drc:ContainerDefinition rdf:ID="cd">
  <drc:name>db</drc:name>
</drc:ContainerDefinition>
```

---

# Properties

## containerDefinition <a name="containerDefinition"> </a>
The definition of a specific container in a docker compose file

### Domain

### Range

### Example
```
```

---

## instance <a name="instance"> </a>

### Domain

### Range

### Example
```
```

---

## instanceOf <a name="instanceOf"> </a>

### Domain

### Range

### Example
```
```

---

## logDefinition <a name="logDefinition"> </a>

### Domain

### Range

### Example
```
```

---

## name <a name="name"> </a>

### Domain

### Range

### Example
```
```

---

## version <a name="version"> </a>

### Domain

### Range

### Example
```
```

---

## volumes <a name="volumes"> </a>

### Domain

### Range

### Example
```
```
