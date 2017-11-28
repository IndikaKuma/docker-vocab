# Docker Ontology

This is an ontology that decribes the docker ecosystem. For the vocabulary that describes docker-compose please see LINK HERE.

![alt-text](https://raw.githubusercontent.com/langens-jonathan/diagrams/master/docker-ontology.png "Docker Vocabulary")

## Prefixes
* <a name="docker">docker</a>: `<https://w3.org/ns/bde/docker#>`
* nie: `<http://www.semanticdesktop.org/ontologies/2007/01/19/nie#>`
* crm: `<http://www.cidoc-crm.org/cidoc-crm/>`
* dct: `<http://purl.org/dc/terms/>`
* rdf: `<http://www.w3.org/1999/02/22-rdf-syntax-ns#>`

## Classes
* [BlockIO](#BlockIO)
* [CPU](#CPU)
* [Config](#Config)
* [Container](#Container)
* [DockerConfig](#DockerConfig)
* [GraphDriver](#GraphDriver)
* [HostConfig](#HostConfig)
* [HostMapping](#HostMapping)
* [Image](#Image)
* [LogConfig](#LogConfig)
* [Mount](#Mount)
* [Network](#Network)
* [NetworkSettings](#NetworkSettings)
* [RepoDigest](#RepoDigest)
* [RepoTags](#RepoTags)
* [RestartPolicy](#RestartPolicy)
* [RootFS](#RootFS)
* [State](#State)

## Properties
* [aliases](#aliases)
* [appArmorProfile](#appArmorProfile)
* [architecture](#architecture)
* [args](#args)
* [argsEscaped](#argsEscaped)
* [attachStream] (#attachStream)
* [authro](#authro)
* [autoRemove](#autoRemove)
* [bind](#bind)
* [blkioDeviceReadBps](#blkioDeviceReadBps)
* [blkioDeviceReadIOps](#blkioDeviceReadIOps)
* [blkioDeviceWriteBps](#blkioDeviceWriteBps)
* [blkioDeviceWriteIOps](#blkioDeviceWriteIOps)
* [blkioWeight](#blkioWeight)
* [blkioWeightDevice](#blkioWeightDevice)
* [bridge](#bridge)
* [capAdd](#capAdd)
* [capDrop](#capDrop)
* [cgroup](#cgroup)
* [cgroupParent](#cgroupParent)
* [cpuCount](#cpuCount)
* [cpuPercent](#cpuPercent)
* [cpuPeriod](#cpuPeriod)
* [cpuQuota](#cpuQuota)
* [cpuRealtimePeriod](#cpuRealtimePeriod)
* [cpuRealtimeRuntime](#cpuRealtimeRuntime)
* [cpusetCpus](#cpusetCpus)
* [cpusetMems](#cpusetMems)
* [cpuShares](#cpuShares)
* [command](#command)
* [comment](#comment)
* [config](#config)
* [consoleSize](#consoleSize)
* [container](#container)
* [containerIDFile](#containerIDFile)
* [created](#created)
* [destination](#destination)
* [deviceCgroupRules](#deviceCgroupRules)
* [devices](#devices)
* [digests](#digests)
* [diskQuota](#diskQuota)
* [dns](#dns)
* [dnsOption](#dnsOption)
* [dnsSearh](#dnsSearh)
* [dockerfileAdd](#dockerfileAdd)
* [dockerfileEnv](#dockerfileEnv)
* [dockerfileExpose](#dockerfileExpose)
* [dockerfileFrom](#dockerfileFrom)
* [dockerfileLabel](#dockerfileLabel)
* [dockerfileStopSignal](#dockerfileStopSignal)
* [dockerfileUser](#dockerfileUser)
* [dockerfileVolume](#dockerfileVolume)
* [dockerfileWorkDir](#dockerfileWorkDir)
* [dockerVersion](#dockerVersion)
* [domainName](#domainName)
* [driver](#driver)
* [endpointID](#endpointID)
* [entrypoint](#entrypoint)
* [env](#env)
* [execIDs](#execIDs)
* [ExitCode](#ExitCode)
* [extraHosts](#extraHosts)
* [FinishedAt](#FinishedAt)
* [gateway](#gateway)
* [globalIPv6Address](#globalIPv6Address)
* [globalIPv6PrefixLen](#globalIPv6PrefixLen)
* [graphDriver](#graphDriver)
* [GraphDriver](#GraphDriver)
* [graphDriverData](#graphDriverData)
* [graphDriverName](#graphDriverName)
* [groupAdd](#groupAdd)
* [hairpinMode](#hairpinMode)
* [hostConfig](#hostConfig)
* [hostName](#hostName)
* [hostnamePath](#hostnamePath)
* [hostsPath](#hostsPath)
* [id](#id)
* [image](#image)
* [intstructionCopy](#intstructionCopy)
* [iOMaximumBandwidth](#iOMaximumBandwidth)
* [iOMaximumIOps](#iOMaximumIOps)
* [iPAddress](#iPAddress)
* [ipamConfig](#ipamConfig)
* [ipcMode](#ipcMode)
* [iPPrefixLen](#iPPrefixLen)
* [iPv6Gateway](#iPv6Gateway)
* [isolation](#isolation)
* [kernelMemory](#kernelMemory)
* [label](#label)
* [layer](#layer)
* [linkLocalIPv6Address](#linkLocalIPv6Address)
* [linkLocalIPv6PrefixLen](#linkLocalIPv6PrefixLen)
* [links](#links)
* [logConfig](#logConfig)
* [logPath](#logPath)
* [logType](#logType)
* [macAddress](#macAddress)
* [maximumRetryCount](#maximumRetryCount)
* [memory](#memory)
* [memoryReservation](#memoryReservation)
* [memorySwap](#memorySwap)
* [memorySwappiness](#memorySwappiness)
* [mode](#mode)
* [mount](#mount)
* [mountLabel](#mountLabel)
* [name](#name)
* [nanoCpus](#nanoCpus)
* [network](#network)
* [networkID](#networkID)
* [networkMode](#networkMode)
* [networkSettings](#networkSettings)
* [onBuild](#onBuild)
* [oomKillDisable](#oomKillDisable)
* [oomScoreAdj](#oomScoreAdj)
* [openStdin](#openStdin)
* [os](#os)
* [parent](#parent)
* [path](#path)
* [Pid](#Pid)
* [pidMode](#pidMode)
* [pidsLimit](#pidsLimit)
* [portBinding](#portBinding)
* [ports](#ports)
* [privileged](#privileged)
* [processLabel](#processLabel)
* [propagation](#propagation)
* [publishedAllPorts](#publishedAllPorts)
* [readonlyRootfs](#readonlyRootfs)
* [resolveConfPath](#resolveConfPath)
* [restartCount](#restartCount)
* [restartPolicy](#restartPolicy)
* [RootFS](#RootFS)
* [rootFSType](#rootFSType)
* [runtime](#runtime)
* [rw](#rw)
* [sandboxID](#sandboxID)
* [sandboxKey](#sandboxKey)
* [secondaryIPAddresses](#secondaryIPAddresses)
* [secondaryIPv6Addresses](#secondaryIPv6Addresses)
* [securityOpt](#securityOpt)
* [shmSize](#shmSize)
* [size](#size)
* [source](#source)
* [state](#state)
* [Status](#Status)
* [StartedAt](#StartedAt)
* [tags](#tags)
* [tty](#tty)
* [ulimits](#ulimits)
* [user](#user)
* [usernsMode](#usernsMode)
* [utsMode](#utsMode)
* [virtualSize](#virtualSize)
* [volume](#volume)
* [volumeDriver](#volumeDriver)
* [volumes](#volumes)
* [workingDir](#workingDir)

## Relations

* [blockIO](#blockIO) 
* [cpu](#cpu)
* [config](#config)
* [dockerfile](#dockerfile)
* [graphDriver](#graphDriver)
* [hostConfig](#hostConfig)
* [hostMapping](#hostMapping)
* [logConfig](#logConfig)
* [mounts](#mounts)
* [network](#network)
* [networkSettings](#networkSettings)
* [repoDigest](#repoDigest)
* [repoTags](#repoTags)
* [restartPolicy](#restartPolicy)
* [rootFS](#rootFS)
* [state](#state)

## docker inspect JSON keys
Here you can find an overview of the keys used by docker inspect when you run either the docker inspect tool on either a container or an image.
* [Aliases] (#AliasesINSPECT)
* [AppArmorProfile] (#AppArmorProfileINSPECT)
* [Architecture] (#ArchitectureINSPECT)
* [Args] (#ArgsINSPECT)
* [ArgsEscaped] (#ArgsEscapedINSPECT)
* [AttachStderr] (#AttachStderrINSPECT)
* [AttachStdin] (#AttachStdinINSPECT)
* [AttachStdout] (#AttachStdoutINSPECT)
* [Author] (#AuthorINSPECT)
* [AutoRemove] (#AutoRemoveINSPECT)
* [Binds] (#BindsINSPECT)
* [BlkioDeviceReadBps] (#BlkioDeviceReadBpsINSPECT)
* [BlkioDeviceReadIOps] (#BlkioDeviceReadIOpsINSPECT)
* [BlkioDeviceWriteBps] (#BlkioDeviceWriteBpsINSPECT)
* [BlkioDeviceWriteIOps] (#BlkioDeviceWriteIOpsINSPECT)
* [BlkioWeight] (#BlkioWeightINSPECT)
* [BlkioWeightDevice] (#BlkioWeightDeviceINSPECT)
* [Bridge] (#BridgeINSPECT)
* [CapAdd] (#CapAddINSPECT)
* [CapDrop] (#CapDropINSPECT)
* [Cgroup] (#CgroupINSPECT)
* [CgroupParent] (#CgroupParentINSPECT)
* [Cmd] (#CmdINSPECT)
* [Comment] (#CommentINSPECT)
* [Config] (#ConfigINSPECT)
* [Config] (#ConfigINSPECT)
* [ConsoleSize] (#ConsoleSizeINSPECT)
* [Container] (#ContainerINSPECT)
* [ContainerIDFile] (#ContainerIDFileINSPECT)
* [CpuCount] (#CpuCountINSPECT)
* [CpuPercent] (#CpuPercentINSPECT)
* [CpuPeriod] (#CpuPeriodINSPECT)
* [CpuQuota] (#CpuQuotaINSPECT)
* [CpuRealtimePeriod] (#CpuRealtimePeriodINSPECT)
* [CpuRealtimeRuntime] (#CpuRealtimeRuntimeINSPECT)
* [CpusetCpus] (#CpusetCpusINSPECT)
* [CpusetMems] (#CpusetMemsINSPECT)
* [CpuShares] (#CpuSharesINSPECT)
* [Created] (#CreatedINSPECT)
* [Created] (#CreatedINSPECT)
* [Data] (#DataINSPECT)
* [Dead] (#DeadINSPECT)
* [Destination] (#DestinationINSPECT)
* [DeviceCgroupRules] (#DeviceCgroupRulesINSPECT)
* [Devices] (#DevicesINSPECT)
* [DiskQuota] (#DiskQuotaINSPECT)
* [Dns] (#DnsINSPECT)
* [DnsOptions] (#DnsOptionsINSPECT)
* [DnsSearch] (#DnsSearchINSPECT)
* [DockerVersion] (#DockerVersionINSPECT)
* [Domainname] (#DomainnameINSPECT)
* [Driver] (#DriverINSPECT)
* [EndpointID] (#EndpointIDINSPECT)
* [EndpointID] (#EndpointIDINSPECT)
* [Entrypoint] (#EntrypointINSPECT)
* [ExecIDs] (#ExecIDsINSPECT)
* [ExitCode] (#ExitCodeINSPECT)
* [ExtraHosts] (#ExtraHostsINSPECT)
* [FinishedAt] (#FinishedAtINSPECT)
* [Gateway] (#GatewayINSPECT)
* [Gateway] (#GatewayINSPECT)
* [GlobalIPv6Address] (#GlobalIPv6AddressINSPECT)
* [GlobalIPv6Address] (#GlobalIPv6AddressINSPECT)
* [GlobalIPv6PrefixLen] (#GlobalIPv6PrefixLenINSPECT)
* [GlobalIPv6PrefixLen] (#GlobalIPv6PrefixLenINSPECT)
* [GraphDriver] (#GraphDriverINSPECT)
* [GroupAdd] (#GroupAddINSPECT)
* [HairpinMode] (#HairpinModeINSPECT)
* [HostConfig] (#HostConfigINSPECT)
* [Hostname] (#HostnameINSPECT)
* [HostnamePath] (#HostnamePathINSPECT)
* [HostsPath] (#HostsPathINSPECT)
* [Id] (#IdINSPECT)
* [Id] (#IdINSPECT)
* [Image] (#ImageINSPECT)
* [Image] (#ImageINSPECT)
* [IOMaximumBandwidth] (#IOMaximumBandwidthINSPECT)
* [IOMaximumIOps] (#IOMaximumIOpsINSPECT)
* [IPAddress] (#IPAddressINSPECT)
* [IPAddress] (#IPAddressINSPECT)
* [IPAMConfig] (#IPAMConfigINSPECT)
* [IpcMode] (#IpcModeINSPECT)
* [IPPrefixLen] (#IPPrefixLenINSPECT)
* [IPPrefixLen] (#IPPrefixLenINSPECT)
* [IPv6Gateway] (#IPv6GatewayINSPECT)
* [IPv6Gateway] (#IPv6GatewayINSPECT)
* [Isolation] (#IsolationINSPECT)
* [KernelMemory] (#KernelMemoryINSPECT)
* [Labels] (#LabelsINSPECT)
* [Layers] (#LayersINSPECT)
* [LinkLocalIPv6Address] (#LinkLocalIPv6AddressINSPECT)
* [Links] (#LinksINSPECT)
* [Links] (#LinksINSPECT)
* [literal] (#literalINSPECT)
* [LogConfig] (#LogConfigINSPECT)
* [LogPath] (#LogPathINSPECT)
* [MacAddress] (#MacAddressINSPECT)
* [MacAddress] (#MacAddressINSPECT)
* [MaximumRetryCount] (#MaximumRetryCountINSPECT)
* [Memory] (#MemoryINSPECT)
* [MemoryReservation] (#MemoryReservationINSPECT)
* [MemorySwap] (#MemorySwapINSPECT)
* [MemorySwappiness] (#MemorySwappinessINSPECT)
* [Mode] (#ModeINSPECT)
* [MountLabel] (#MountLabelINSPECT)
* [Mounts] (#MountsINSPECT)
* [Name] (#NameINSPECT)
* [Name] (#NameINSPECT)
* [Name] (#NameINSPECT)
* [Name] (#NameINSPECT)
* [NanoCpus] (#NanoCpusINSPECT)
* [NetworkID] (#NetworkIDINSPECT)
* [NetworkMode] (#NetworkModeINSPECT)
* [Networks] (#NetworksINSPECT)
* [NetworkSettings] (#NetworkSettingsINSPECT)
* [OomKillDisable] (#OomKillDisableINSPECT)
* [OOMKilled] (#OOMKilledINSPECT)
* [OomScoreAdj] (#OomScoreAdjINSPECT)
* [OpenStdin] (#OpenStdinINSPECT)
* [Os] (#OsINSPECT)
* [Parent] (#ParentINSPECT)
* [Path] (#PathINSPECT)
* [Paused] (#PausedINSPECT)
* [Pid] (#PidINSPECT)
* [PidMode] (#PidModeINSPECT)
* [PidsLimit] (#PidsLimitINSPECT)
* [PortBindings] (#PortBindingsINSPECT)
* [Ports] (#PortsINSPECT)
* [Privileged] (#PrivilegedINSPECT)
* [ProcessLabel] (#ProcessLabelINSPECT)
* [Propagation] (#PropagationINSPECT)
* [PublishAllPorts] (#PublishAllPortsINSPECT)
* [ReadonlyRootfs] (#ReadonlyRootfsINSPECT)
* [RepoDigests] (#RepoDigestsINSPECT)
* [RepoTags] (#RepoTagsINSPECT)
* [ResolvConfPath] (#ResolvConfPathINSPECT)
* [RestartCount] (#RestartCountINSPECT)
* [Restarting] (#RestartingINSPECT)
* [RestartPoliciy] (#RestartPoliciyINSPECT)
* [Running] (#RunningINSPECT)
* [Runtime] (#RuntimeINSPECT)
* [RW] (#RWINSPECT)
* [SandboxID] (#SandboxIDINSPECT)
* [SandboxKey] (#SandboxKeyINSPECT)
* [SecondaryIPAddresses] (#SecondaryIPAddressesINSPECT)
* [SecondaryIPv6Addresses] (#SecondaryIPv6AddressesINSPECT)
* [SecurityOpt] (#SecurityOptINSPECT)
* [ShmSize] (#ShmSizeINSPECT)
* [Size] (#SizeINSPECT)
* [Source] (#SourceINSPECT)
* [StartedAt] (#StartedAtINSPECT)
* [State] (#StateINSPECT)
* [Status] (#StatusINSPECT)
* [Tty] (#TtyINSPECT)
* [Type] (#TypeINSPECT)
* [Type] (#TypeINSPECT)
* [Ulimits] (#UlimitsINSPECT)
* [User] (#UserINSPECT)
* [UsernsMode] (#UsernsModeINSPECT)
* [UTSMode] (#UTSModeINSPECT)
* [VirtualSize] (#VirtualSizeINSPECT)
* [VolumeDrive] (#VolumeDriveINSPECT)
* [WorkingDir] (#WorkingDirINSPECT)

# Container State Concept Scheme
We define a concept scheme indicating the state of a container. This means that if the docker inspect value of a container is:
```
{
        "Id": "b10b23a01d3fd2611841f2b908fadb67cfaebd7af065914a2f40bb750326d078",
        "Created": "2017-10-10T14:36:33.842053654Z",
        .
        .
        .
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 8638,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2017-10-10T14:36:34.360284997Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:4f2ae851ed29a92ae380c5b3872198193affba4cbffb15e43ff10475a131be17",
        .
        .
        .
```
That this will result in this docker having the relationship
```
<http://..../docker/b10b23...6d078> <hasState> docker:Running .
```

## States
* [Dead](#Dead)
* [OOMKilled](#OOMKilled)
* [Paused](#Paused)
* [Restarting](#Restarting)
* [Running](#Running)

# Classes
<a name="BlockIO"></a>
## BlockIO
#### Description
The BlockIO configuration information

#### Equivalent
none

#### Properties
| Predicate                                                       | Owl:same-as | Docker Inspect Value   | Type           | Arity |
| :---:                                                           | :---:       | :---:                  | :---:          | :---: |
| [docker](#docker):[blkioWeight](#blkioWeight)                   |             | "BlkioWeight"          | literal:number | 1-1   |
| [docker](#docker):[blkioWeightDevice](#blkioWeightDevice)       |             | "BlkioWeightDevice"    | literal:string | 1-1   |
| [docker](#docker):[blkioDeviceReadBps](#blkioDeviceReadBps)     |             | "BlkioDeviceReadBps"   | literal:string | 1-1   |
| [docker](#docker):[blkioDeviceWriteBps](#blkioDeviceWriteBps)   |             | "BlkioDeviceWriteBps"  | literal:string | 1-1   |
| [docker](#docker):[blkioDeviceReadIOps](#blkioDeviceReadIOps)   |             | "BlkioDeviceReadIOps"  | literal:string | 1-1   |
| [docker](#docker):[blkioDeviceWriteIOps](#blkioDeviceWriteIOps) |             | "BlkioDeviceWriteIOps" | literal:string | 1-1   |

#### Relations

##### Domain of

##### Range of 
* [docker:blockIO](#blockIO)

#### Example
```
```

---

<a name="CPU"></a>
## CPU
#### Description
The BlockIO configuration information

#### Equivalent
none

#### Properties
| Predicate                                                   | Owl:same-as | Docker Inspect Value | Type           | Arity |
| :---:                                                       | :---:       | :---:                | :---:          | :---: |
| [docker](#docker):[cpuPeriod](#cpuPeriod)                   |             | "CpuPeriod"          | literal:number | 1-1   |
| [docker](#docker):[cpuQuota](#cpuQuota)                     |             | "CpuQuota"           | literal:number | 1-1   |
| [docker](#docker):[cpuRealtimePeriod](#cpuRealtimePeriod)   |             | "CpuRealtimePeriod"  | literal:number | 1-1   |
| [docker](#docker):[cpuRealtimeRuntime](#cpuRealtimeRuntime) |             | "CpuRealtimeRuntime" | literal:number | 1-1   |
| [docker](#docker):[cpusetCpus](#cpusetCpus)                 |             | "CpusetCpus"         | literal:string | 1-1   |
| [docker](#docker):[cpusetMems](#cpusetMems)                 |             | "CpusetMems"         | literal:string | 1-1   |
| [docker](#docker):[cpuCount](#cpuCount)                     |             | "CpuCount"           | literal:number | 1-1   |
| [docker](#docker):[cpuPercent](#cpuPercent)                 |             | "CpuPercent"         | literal:number | 1-1   |

#### Relations

##### Domain of

##### Range of 
* [docker:cpu](#cpu)

#### Example
```
```

---




<a name="State"></a>
## State

#### Description

#### Equivalent
none

#### Properties
| Predicate                                   | Owl:same-as | Docker Inspect Value   | Type              | Arity |
| :--------------------------------------:    | :---------: | :--------------------: | :---------------: | :-:   |
| [docker](#docker):[status](#status)         |             | "Status"               | literal:string    | 1-1   |
| [docker](#docker):[pid](#pid)               | dct:id      | "Pid"                  | literal:number    | 1-1   |
| [docker](#docker):[exitCode](#exitCode)     |             | "ExitCode"             | literal:string    | 1-1   |
| [docker](#docker):[startedAt](#startedAt)   |             | "StartedAt"            | literal:date      | 1-1   |
| [docker](#docker):[finishedAt](#finishedAt) |             | "FinishedAt"           | literal:date      | 1-1   |

#### Relations

##### Domain of

##### Range of 
* [docker:state](#state)

#### Example
```
```

---

<a name="HostConfig"></a>
## HostConfig

#### Description

#### Equivalent
none

#### Properties
| Predicate                                                   | Owl:same-as | Docker Inspect Value     | Type                   | Arity   |
| :---------------------                                      | :------:    | :----------------------: | :--------------------: | :-----: |
| [docker](#docker):[bind](#bind)                             |             |                          | literal:string         |   1-n   |
| [docker](#docker):[containerIDFile](#containerIDFile)       |             | ContainerIDFile          | literal:string         |   1-1   |
| [docker](#docker):[networkMode](#networkMode)               |             | NetworkMode              | literal:string         |   1-1   |
| [docker](#docker):[autoRemove](#autoRemove)                 |             | AutoRemove               | literal:boolean        |   1-1   |
| [docker](#docker):[volumeDriver](#volumeDriver)             |             | VolumeDrive              | literal:string         |   1-1   |
| [docker](#docker):[capAdd](#capAdd)                         |             | CapAdd                   | literal:string         |   1-1   |
| [docker](#docker):[capDrop](#capDrop)                       |             | CapDrop                  | literal:string         |   1-1   |
| [docker](#docker):[dns](#dns)                               |             | Dns                      | literal:string         |   1-1   |
| [docker](#docker):[dnsOption](#dnsOption)                   |             | DnsOptions               | literal:string         |   1-n   |
| [docker](#docker):[dnsSearh](#dnsSearh)                     |             | DnsSearch                | literal:string         |   1-n   |
| [docker](#docker):[extraHosts](#extraHosts)                 |             | ExtraHosts               | literal:string         |   1-1   |
| [docker](#docker):[groupAdd](#groupAdd)                     |             | GroupAdd                 | literal:string         |   1-1   |
| [docker](#docker):[ipcMode](#ipcMode)                       |             | IpcMode                  | literal:string         |   1-1   |
| [docker](#docker):[cgroup](#cgroup)                         |             | Cgroup                   | literal:string         |   1-1   |
| [docker](#docker):[oomScoreAdj](#oomScoreAdj)               |             | OomScoreAdj              | literal:string         |   1-1   |
| [docker](#docker):[pidMode](#pidMode)                       |             | PidMode                  | literal:string         |   1-1   |
| [docker](#docker):[privileged](#privileged)                 |             | Privileged               | literal:boolean        |   1-1   |
| [docker](#docker):[publishedAllPorts](#publishedAllPorts)   |             | PublishAllPorts          | literal:boolean        |   1-1   |
| [docker](#docker):[readonlyRootfs](#readonlyRootfs)         |             | ReadonlyRootfs           | literal:boolean        |   1-1   |
| [docker](#docker):[securityOpt](#securityOpt)               |             | SecurityOpt              | literal:string         |   1-1   |
| [docker](#docker):[utsMode](#utsMode)                       |             | UTSMode                  | literal:string         |   1-1   |
| [docker](#docker):[usernsMode](#usernsMode)                 |             | UsernsMode               | literal:string         |   1-1   |
| [docker](#docker):[shmSize](#shmSize)                       |             | ShmSize                  | literal:number         |   1-1   |
| [docker](#docker):[runtime](#runtime)                       |             | Runtime                  | literal:string         |   1-1   |
| [docker](#docker):[consoleSize](#consoleSize)               |             | ConsoleSize              | literal:string         |   1-1   |
| [docker](#docker):[isolation](#isolation)                   |             | Isolation                | literal:string         |   1-1   |
| [docker](#docker):[cpuShares](#cpuShares)                   |             | CpuShares                | literal:number         |   1-1   |
| [docker](#docker):[memory](#memory)                         |             | Memory                   | literal:number         |   1-1   |
| [docker](#docker):[nanoCpus](#nanoCpus)                     |             | NanoCpus                 | literal:number         |   1-1   |
| [docker](#docker):[cgroupParent](#cgroupParent)             |             | CgroupParent             | literal:string         |   1-1   |
| [docker](#docker):[deviceCgroupRules](#deviceCgroupRules)   |             | DeviceCgroupRules        | literal:string         |   1-1   |
| [docker](#docker):[diskQuota](#diskQuota)                   |             | DiskQuota                | literal:number         |   1-1   |
| [docker](#docker):[kernelMemory](#kernelMemory)             |             | KernelMemory             | literal:number         |   1-1   |
| [docker](#docker):[memoryReservation](#memoryReservation)   |             | MemoryReservation        | literal:number         |   1-1   |
| [docker](#docker):[memorySwap](#memorySwap)                 |             | MemorySwap               | literal:number         |   1-1   |
| [docker](#docker):[memorySwappiness](#memorySwappiness)     |             | MemorySwappiness         | literal:number         |   1-1   |
| [docker](#docker):[oomKillDisable](#oomKillDisable)         |             | OomKillDisable           | literal:boolean        |   1-1   |
| [docker](#docker):[pidsLimit](#pidsLimit)                   |             | PidsLimit                | literal:number         |   1-1   |
| [docker](#docker):[ulimits](#ulimits)                       |             | Ulimits                  | literal:string         |   1-1   |
| [docker](#docker):[iOMaximumIOps](#iOMaximumIOps)           |             | IOMaximumIOps            | literal:number         |   1-1   |
| [docker](#docker):[iOMaximumBandwidth](#iOMaximumBandwidth) |             | IOMaximumBandwidth       | literal:number         |   1-1   |

#### Relations

##### Domain of
* [docker:cpu](#cpu)
* [docker:blockIO](#blockIO)
* [docker:logConfig](#logConfig)
* [docker:restartPolicy](#restartPolicy)

##### Range of 
* [docker:hostConfig](#hostConfig)

#### Example
```
```

---

<a name="Container"></a>
## Container

#### Description

#### Equivalent
none

#### Properties
| Predicate                                             | OWL:sameAs       | Docker Inspect Value     | Type                   | Arity   |
| :---------------------------                          | :--------------: | :----------------------: | :--------------------: | :-----: |
| [docker](#docker):[id](#id)                           | dct:id           | "Id"                     | literal:string         |   1-1   |
| [docker](#docker):[created](#created)                 | dct:createdAt    | "Created"                | literal:date           |   1-1   |
| [docker](#docker):[path](#path)                       |                  | "Path"                   | literal :string        |   1-1   |
| [docker](#docker):[args](#args)                       |                  | "Args"                   | literal:string         |   1=*   |
| [docker](#docker):[resolveConfPath](#resolveConfPath) |                  | "ResolvConfPath"         | literal:string         |   1-1   |
| [docker](#docker):[hostnamePath](#hostnamePath)       |                  | "HostnamePath"           | literal:string         |   1-1   |
| [docker](#docker):[hostsPath](#hostsPath)             |                  | "HostsPath"              | literal:string         |   1-1   |
| [docker](#docker):[logPath](#logPath)                 |                  | "LogPath"                | literal:string         |   1-1   |
| [docker](#docker):[name](#name)                       | dct:title        | "Name"                   | literal:string         |   1-1   |
| [docker](#docker):[restartCount](#restartCount)       |                  | "RestartCount"           | literal:number         |   1-1   |
| [docker](#docker):[mountLabel](#mountLabel)           |                  | "MountLabel"             | literal:string         |   1-1   |
| [docker](#docker):[processLabel](#processLabel)       |                  | "ProcessLabel"           | literal:string         |   1-1   |
| [docker](#docker):[appArmorProfile](#appArmorProfile) |                  | "AppArmorProfile"        | literal:string         |   1-1   |
| [docker](#docker):[execIDs](#execIDs)                 |                  | "ExecIDs"                | literal:string         |   1-1   |

#### Relations

##### Domain of
* [docker:networkSetting](#networkSetting)
* [docker:config](#config)
* [docker:state](#state)
* [docker:graphDriver](#graphDriver)
* [docker:mount](#mount)

##### Range of 

#### Example
```
```

---

<a name="LogConfig"></a>
## LogConfig

#### Description

#### Equivalent
none

#### Properties
| Predicate                             | OWL:sameAs       | Docker Inspect Value     | Type                   | Arity   |
| :---------------------------          | :--------------: | :----------------------: | :--------------------: | :-----: |
| [docker](#docker):[logType](#logType) | dct:format       | "Type"                   | literal:string         |   1-1   |

#### Relations

##### Domain of

##### Range of 
* [docker:logconfig](#logconfig)

#### Example
```
```

---

<a name="RestartPolicy"></a>
## RestartPolicy

#### Description

#### Equivalent
none

#### Properties
| Predicate                                                 | OWL:sameAs       | Docker Inspect Value     | Type                   | Arity   |
| :---------------------------                              | :--------------: | :----------------------: | :--------------------: | :-----: |
| [docker](#docker):[name](#name)                           | dct:title        | "Name"                   | literal:string         |   1-1   |
| [docker](#docker):[maximumRetryCount](#maximumRetryCount) |                  | "maximumRetryCount"      | literal:number         |   1-1   |


#### Relations

##### Domain of

##### Range of 
* [docker:restartPolicy](#restartPolicy)

#### Example
```
```

---

<a name="Mount"></a>
## Mount

#### Description

#### Equivalent
none

#### Properties
| Predicate                                     | OWL:sameAs       | Docker Inspect Value     | Type                   | Arity   |
| :---------------------------                  | :--------------: | :----------------------: | :--------------------: | :-----: |
| [docker](#docker):[name](#name)               | dct:title        | "Name"                   | literal:string         |   1-1   |
| [docker](#docker):[source](#source)           | dct:source       | "Source"                 | literal:string         |   1-1   |
| [docker](#docker):[destination](#destination) |                  | "Destination"            | literal:string         |   1-1   |
| [docker](#docker):[driver](#driver)           |                  | "Driver"                 | literal:string         |   1-1   |
| [docker](#docker):[mode](#mode)               |                  | "Mode"                   | literal:string         |   1-1   |
| [docker](#docker):[rw](#rw)                   |                  | "RW"                     | literal:boolean        |   1-1   |
| [docker](#docker):[propagation](#propagation) |                  | "Propagation"            | literal:string         |   1-1   |


#### Relations

##### Domain of

##### Range of 
* [docker:mount](#mount)

#### Example
```
```

---


<a name="NetworkSettings"></a>
## NetworkSettings

#### Description

#### Equivalent
none

#### Properties
| Predicate                                                           | OWL:sameAs       | Docker Inspect Value     | Type                   | Arity   |
| :---------------------------                                        | :--------------: | :----------------------: | :--------------------: | :-----: |
| [docker](#docker):[bridge](#bridge)                                 |                  | "Bridge"                 | literal:string         |   1-1   |
| [docker](#docker):[sandboxID](#sandboxID)                           |                  | "SandboxID"              | literal:string         |   1-1   |
| [docker](#docker):[hairpinMode](#hairpinMode)                       |                  | "HairpinMode"            | literal:boolean        |   1-1   |
| [docker](#docker):[linkLocalIPv6Address](#linkLocalIPv6Address)     |                  | "LinkLocalIPv6Address"   | literal:string         |   1-1   |
| [docker](#docker):[linkLocalIPv6PrefixLen](#linkLocalIPv6PrefixLen) |                  | "linkLocalIPv6PrefixLen" | literal:number         |   1-1   |
| [docker](#docker):[sandboxKey](#sandboxKey)                         |                  | "SandboxKey"             | literal:string         |   1-1   |
| [docker](#docker):[secondaryIPAddresses](#secondaryIPAddresses)     |                  | "SecondaryIPAddresses"   | literal:string         |   1-1   |
| [docker](#docker):[secondaryIPv6Addresses](#secondaryIPv6Addresses) |                  | "SecondaryIPv6Addresses" | literal:string         |   1-1   |
| [docker](#docker):[endpointID](#endpointID)                         |                  | "EndpointID"             | literal:string         |   1-1   |
| [docker](#docker):[gateway](#gateway)                               |                  | "Gateway"                | literal:string         |   1-1   |
| [docker](#docker):[globalIPv6Address](#globalIPv6Address)           |                  | "GlobalIPv6Address"      | literal:string         |   1-1   |
| [docker](#docker):[globalIPv6PrefixLen](#globalIPv6PrefixLen)       |                  | "GlobalIPv6PrefixLen"    | literal:number         |   1-1   |
| [docker](#docker):[iPAddress](#iPAddress)                           |                  | "IPAddress"              | literal:string         |   1-1   |
| [docker](#docker):[iPPrefixLen](#iPPrefixLen)                       |                  | "IPPrefixLen"            | literal:number         |   1-1   |
| [docker](#docker):[iPv6Gateway](#iPv6Gateway)                       |                  | "IPv6Gateway"            | literal:string         |   1-1   |
| [docker](#docker):[macAddress](#macAddress)                         |                  | "MacAddress"             | literal:string         |   1-1   |



#### Relations

##### Domain of
* [docker:networkSettings](#networkSettings)

##### Range of 
* [docker:network](#network)
* [docker:hostMapping](#hostMapping)

#### Example
```
```

---

<a name="Network"></a>
## Network

#### Description

#### Equivalent
none

#### Properties
| Predicate                                                     | OWL:sameAs       | Docker Inspect Value     | Type                   | Arity   |
| :---------------------------                                  | :--------------: | :----------------------: | :--------------------: | :-----: |
| [docker](#docker):[name](#name)                               | dct:title        | "Name"                   | literal:string         |   1-1   |
| [docker](#docker):[maximumRetryCount](#maximumRetryCount)     |                  | "maximumRetryCount"      | literal:number         |   1-1   |
| [docker](#docker):[ipamConfig](#ipamConfig)                   |                  | "IPAMConfig"             | literal:string         |   1-1   |
| [docker](#docker):[links](#links)                             |                  | "Links"                  | literal:string         |   1-1   |
| [docker](#docker):[aliases](#aliases)                         |                  | "Aliases"                | literal:string         |   1-1   |
| [docker](#docker):[networkID](#networkID)                     |                  | "NetworkID"              | literal:string         |   1-1   |
| [docker](#docker):[endpointID](#endpointID)                   |                  | "EndpointID"             | literal:string         |   1-1   |
| [docker](#docker):[gateway](#gateway)                         |                  | "Gateway"                | literal:string         |   1-1   |
| [docker](#docker):[iPAddress](#iPAddress)                     |                  | "IPAddress"              | literal:string         |   1-1   |
| [docker](#docker):[iPPrefixLen](#iPPrefixLen)                 |                  | "IPPrefixLen"            | literal:number         |   1-1   |
| [docker](#docker):[iPv6Gateway](#iPv6Gateway)                 |                  | "IPv6Gateway"            | literal:string         |   1-1   |
| [docker](#docker):[globalIPv6Address](#globalIPv6Address)     |                  | "GlobalIPv6Address"      | literal:string         |   1-1   |
| [docker](#docker):[globalIPv6PrefixLen](#globalIPv6PrefixLen) |                  | "GlobalIPv6PrefixLen"    | literal:number         |   1-1   |
| [docker](#docker):[macAddress](#macAddress)                   |                  | "MacAddress"             | literal:string         |   1-1   |


#### Relations

##### Domain of

##### Range of 
* [docker:network](#network)

#### Example
```
```

---

<a name="Image"></a>
## Image

#### Description

#### Equivalent
none

#### Properties
| Predicate                                         | OWL:sameAs       | Docker Inspect Value     | Type                   | Arity   |
| :---------------------------                      | :--------------: | :----------------------: | :--------------------: | :-----: |
| [docker](#docker):[id](#id)                       | dct:title        | "Id"                     | literal:string         | 1-1     |
| [docker](#docker):[tags](#tags)                   |                  | "RepoTags"               | literal:string         | 1-n     |
| [docker](#docker):[digests](#digests)             |                  | "RepoDigests"            | literal:string         | 1-n     |
| [docker](#docker):[parent](#parent)               |                  | "Parent"                 | literal:string         |   1-1   |
| [docker](#docker):[comment](#comment)             |                  | "Comment"                | literal:string         |   1-1   |
| [docker](#docker):[created](#created)             | dct:created      | "Created"                | literal:date           |   1-1   |
| [docker](#docker):[dockerVersion](#dockerVersion) |                  | "DockerVersion"          | literal:string         |   1-1   |
| [docker](#docker):[author](#author)               | dct:creator      | "Author"                 | literal:string         |   1-1   |
| [docker](#docker):[architecture](#architecture)   |                  | "Architecture"           | literal:string         |   1-1   |
| [docker](#docker):[os](#os)                       |                  | "Os"                     | literal:string         |   1-1   |
| [docker](#docker):[size](#size)                   |                  | "Size"                   | literal:number         |   1-1   |
| [docker](#docker):[virtualSize](#virtualSize)     |                  | "VirtualSize"            | literal:number         |   1-1   |



#### Relations

##### Domain of
* [docker:config](#config)
* [docker:dockerfile](#dockerfile)
* [docker:graphDriver](#graphDriver)
* [docker:repoTags](#repoTags)
* [docker:repoDigest](#repoDigest)
* [docker:rootFS](#rootFS)

##### Range of 

#### Example
```
```

---


<a name="RootFS"></a>
## RootFS

#### Description

#### Equivalent
none

#### Properties
| Predicate                                   | OWL:sameAs       | Docker Inspect Value     | Type                   | Arity   |
| :---------------------------                | :--------------: | :----------------------: | :--------------------: | :-----: |
| [docker](#docker):[rootFSType](#rootFSType) |                  | "Type"                   | literal:string         |   1-1   |
| [docker](#docker):[layer](#layer)           |                  | "Layers"                 | literal:string         |   1-n   |


#### Relations

##### Domain of

##### Range of 
* [docker:rootFS](#rootFS)

#### Example
```
```

---


<a name="GraphDriver"></a>
## GraphDriver

#### Description

#### Equivalent
none

#### Properties
| Predicate                                             | OWL:sameAs       | Docker Inspect Value     | Type                   | Arity   |
| :---------------------------                          | :--------------: | :----------------------: | :--------------------: | :-----: |
| [docker](#docker):[graphDriverData](#graphDriverData) |                  | "Data"                   | literal:string         |   1-1   |
| [docker](#docker):[graphDriverName](#graphDriverName) | dct:title        | "Name"                   | literal:string         |   1-1   |


#### Relations

##### Domain of

##### Range of 
* [docker:graphDriver](#graphDriver)

#### Example
```
```

---

<a name="DockerConfig"></a>
## DockerConfig
Configuration for a container that is portable between hosts.
[More info here](#https://docs.docker.com/engine/api/v1.31/#operation/ImageInspect)

#### Description

#### Equivalent
none

#### Properties
| Predicate                                             | OWL:sameAs       | Docker Inspect Value     | Type                   | Arity   |
| :---------------------------                          | :--------------: | :----------------------: | :--------------------: | :-----: |
| [docker](#docker):[hostName](#hostName)               |                  | "Hostname"               | literal:string         |   1-1   |
| [docker](#docker):[domainName](#domainName)           |                  | "Domainname"             | literal:string         |   1-1   |
| [docker](#docker):[user](#user)                       |                  | "User"                   | literal:string         |   1-1   |
| [docker](#docker):[attachStream](#attachStream)       |                  | "AttachStream"           | literal:boolean        |   1-1   |
| [docker](#docker):[tty](#tty)                         |                  | "Tty"                    | literal:boolean        |   1-1   |
| [docker](#docker):[openStdin](#openStdin)             |                  | "OpenStdin"              | literal:boolean        |   1-1   |
| [docker](#docker):[command](#command)                 |                  | "Cmd"                    | literal:string         |   1-n   |
| [docker](#docker):[argsEscaped](#argsEscaped)         |                  | "ArgsEscaped"            | literal:boolean        |   1-1   |
| [docker](#docker):[workingDir](#workingDir)           |                  | "WorkingDir"             | literal:string         |   1-1   |
| [docker](#docker):[entrypoint](#entrypoint)           |                  | "Entrypoint"             | literal:string         |   1-1   |
| [docker](#docker):[onBuild](#onBuild)                 |                  | "onBuild"                | literal:string         |   1-1   |
| [docker](#docker):[label](#label)                     |                  | "Labels"                 | literal:string         |   1-n   |


#### Relations

##### Domain of
* [docker:graphDriver](#graphDriver)

##### Range of 
* [docker:dockerConfig](#dockerConfig)

#### Example
```
```

---

# Properties
<a name="aliases"> </a>
## aliases

#### predicate
docker:aliases

### docker inspect value
"Aliases"

### Domain
* [Network](#Network)

### Range
literal (string)

### Examples
```
```

---

<a name="appArmorProfile"> </a>
## appArmorProfile

### predicate
docker:appArmorProfile

### docker inspect value
"AppArmorProfile"

### Domain
[Container](#Container)

### Range
literal (string)

### Examples
```
```

---

<a name="architecture"> </a>
## architecture

### predicate
docker:architecture

### docker inspect value
"Architecture"

### Domain
[Image](#Image)

### Range
literal (string)

### Examples
```
```

---

<a name="args"> </a>
## args
This is a one on many relation and is represented as a JSON array in the inspect produced by docker.

### predicate
docker:args

### docker inspect value
"Args"

### Domain
[Container](#Container)

### Range
literal (string)

### Examples
```
```

---

<a name="argsEscaped"> </a>
## argsEscaped

### predicate
docker:argsEscaped

### docker inspect value
"ArgsEscaped"

### Domain
[DockerConfig](#DockerConfig)

### Range
literal (boolean)

### Examples
```
```

---

<a name="attachStream"> </a>
## attachStream
Used to describe the connection of a stream to a container. Although the range of this predicate is SKOS:Concept there is also an ontology that describes the different streams (stderr, stdin, stdout).

### predicate
docker:attachStream

### docker inspect value
"AttachStderr"
"AttachStdin"
"AttachStdout"

### Domain
[DockerConfig](#DockerConfig)

### Range
SKOS:Concept

### Examples
```
```

---


<a name="author"> </a>
## author

### predicate
docker:author

### docker inspect value
"Author"

### Domain
[Image](#Image)

### Range
literal (string)

### Examples
```
```

---

<a name="autoRemove"> </a>
## autoRemove

### predicate
docker:autoRemove

### docker inspect value
"AutoRemove"

### Domain
[HostConfig](#HostConfig)

### Range
literal (boolean)

### Examples
```
```

---

<a name="bind"> </a>
## bind
This is a one on many relation and is represented as a JSON array in the inspect produced by docker.

### predicate
docker:bind

### docker inspect value
"Binds"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="blkioDeviceReadBps"> </a>
## blkioDeviceReadBps

### predicate
docker:blkioDeviceReadBps

### docker inspect value
"BlkioDeviceReadBps"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="blkioDeviceReadIOps"> </a>
## blkioDeviceReadIOps

### predicate
docker:blkioDeviceReadIOps

### docker inspect value
"BlkioDeviceReadIOps"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="blkioDeviceWriteBps"> </a>
## blkioDeviceWriteBps

### predicate
docker:blkioDeviceWriteBps

### docker inspect value
"BlkioDeviceWriteBps"

### Domain
[HostConfig](#HostConfig)

### Range
: literal (string)

### Examples
```
```

---

<a name="blkioDeviceWriteIOps"> </a>
## blkioDeviceWriteIOps

### predicate
docker:blkioDeviceWriteIOps

### docker inspect value
"BlkioDeviceWriteIOps"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="blkioWeight"> </a>
## blkioWeight

### predicate
docker:blkioWeight

### docker inspect value
"BlkioWeight"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="blkioWeightDevice"> </a>
## blkioWeightDevice

### predicate
docker:blkioWeightDevice

### docker inspect value
"BlkioWeightDevice"

### Domain
[HostConfig](#HostConfig)

### RANGE
literal (string)

### Examples
```
```

---

<a name="bridge"> </a>
## bridge

### predicate
docker:bridge

### docker inspect value
"Bridge"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (string)

### Examples
```
```

---

<a name="capAdd"> </a>
## capAdd

### predicate
docker:capAdd

### docker inspect value
"CapAdd"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="capDrop"> </a>
## capDrop

### predicate
docker:capDrop

### docker inspect value
"CapDrop"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="cgroup"> </a>
## cgroup

### predicate
docker:cgroup

### docker inspect value
"Cgroup"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="cgroupParent"> </a>
## cgroupParent

### predicate
docker:cgroupParent

### docker inspect value
"CgroupParent"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="command"> </a>
## command
This is a one on many relation and is represented as a JSON array in the inspect produced by docker.

### predicate
docker:command

### docker inspect value
"Cmd"

### Domain
[DockerConfig](#DockerConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="comment"> </a>
## comment

### predicate
docker:comment

### docker inspect value
"Comment"

### Domain
[Image](#Image)

### Range
literal (string)

### Examples
```
```

---

<a name="consoleSize"> </a>
## consoleSize

### predicate
docker:consoleSize

### docker inspect value
"ConsoleSize"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="containerIDFile"> </a>
## containerIDFile

### predicate
docker:containerIDFile

### docker inspect value
"ContainerIDFile"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="cpuCount"> </a>
## cpuCount

### predicate
docker:cpuCount

### docker inspect value
"CpuCount"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="cpuPercent"> </a>
## cpuPercent

### predicate
docker:cpuPercent

### docker inspect value
"CpuPercent"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="cpuPeriod"> </a>
## cpuPeriod

### predicate
docker:cpuPeriod

### docker inspect value
"CpuPeriod"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="cpuQuota"> </a>
## cpuQuota

### predicate
docker:cpuQuota

### docker inspect value
"CpuQuota"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="cpuRealtimePeriod"> </a>
## cpuRealtimePeriod

### predicate
docker:cpuRealtimePeriod

### docker inspect value
"CpuRealtimePeriod"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="cpuRealtimeRuntime"> </a>
## cpuRealtimeRuntime

### predicate
docker:cpuRealtimeRuntime

### docker inspect value
"CpuRealtimeRuntime"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="cpusetCpus"> </a>
## cpusetCpus

### predicate
docker:cpusetCpus

### docker inspect value
"CpusetCpus"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="cpusetMems"> </a>
## cpusetMems

### predicate
docker:cpusetMems

### docker inspect value
"CpusetMems"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="cpuShares"> </a>
## cpuShares

### predicate
docker:cpuShares

### docker inspect value
"CpuShares"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="created"> </a>
## created

### predicate
docker:created

### docker inspect value
"Created"

### Domain
[Image](#Image)

### Range
literal:date 

### Examples
```
```

---

<a name="created"> </a>
## created

### predicate
docker:created

#### owl:sameAs
dct:createdAt

### docker inspect value
"Created"

### Domain
[Container](#Container)

### Range
literal (date)

### Examples
```
```

---

<a name="dead"> </a>
## dead

### predicate
docker:dead

### docker inspect value
"Dead"

### Domain
[State](#State)

### Range
literal (boolean)

### Examples
```
```

---

<a name="destination"> </a>
## destination

### predicate
docker:destination

### docker inspect value
"Destination"

### Domain
[Mount](#Mount)

### Range
literal (string)

### Examples
```
```

---

<a name="deviceCgroupRules"> </a>
## deviceCgroupRules

### predicate
docker:deviceCgroupRules

### docker inspect value
"DeviceCgroupRules"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="digests"> </a>
## digests
This is a one on many relation and is represented as a JSON array in the inspect produced by docker.

### predicate
docker:digests

### docker inspect value
"RepoDigests"

### Domain
[Image](#Image)

### Range
literal (string)

### Examples
```
```

---

<a name="diskQuota"> </a>
## diskQuota

### predicate
docker:diskQuota

### docker inspect value
"DiskQuota"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="dns"> </a>
## dns

### predicate
docker:dns

### docker inspect value
"Dns"

### Domain
[(1-*) HostConfig](#(1-*) HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="dnsOption"> </a>
## dnsOption

### predicate
docker:dnsOption

### docker inspect value
"DnsOptions"

### Domain
[(1-*) HostConfig](#(1-*) HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="dnsSearh"> </a>
## dnsSearh

### predicate
docker:dnsSearh

### docker inspect value
"DnsSearch"

### Domain
[(1-*) HostConfig](#(1-*) HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="dockerfileAdd"> </a>
## dockerfileAdd

### predicate
docker:dockerfileAdd

### Dockerfile value
ADD

### Domain
[Dockerfile](#Dockerfile)

### Range
literal (string)

### Examples
```
```

---

<a name="dockerfileEnv"> </a>
## dockerfileEnv

### predicate
docker:dockerfileEnv

### Dockerfile value
ENV

### Domain
[Dockerfile](#Dockerfile)

### Range
literal (string)

### Examples
```
```

---

<a name="dockerfileExpose"> </a>
## dockerfileExpose

### predicate
docker:dockerfileExpose

### Dockerfile value
EXPOSE

### Domain
[Dockerfile](#Dockerfile)

### Range
literal (string)

### Examples
```
```

---

<a name="dockerfileFrom"> </a>
## dockerfileFrom

### predicate
docker:dockerfileFrom

### docker inspect value
FROM

### Domain
[Dockerfile](#Dockerfile)

### Range
literal (string)

### Examples
```
```

---

<a name="dockerfileLabel"> </a>
## dockerfileLabel

### predicate
docker:dockerfileLabel

### docker inspect value
LABEL

### Domain
[Dockerfile](#Dockerfile)

### Range
literal (string)

### Examples
```
```

---

<a name="dockerfileStopSignal"> </a>
## dockerfileStopSignal

### predicate
docker:dockerfileStopSignal

### docker inspect value
STOPSIGNAL

### Domain
[Dockerfile](#Dockerfile)

### Range
literal (string)

### Examples
```
```

---

<a name="dockerfileUser"> </a>
## dockerfileUser

### predicate
docker:dockerfileUser

### docker inspect value
USER

### Domain
[Dockerfile](#Dockerfile)

### Range
literal (string)

### Examples
```
```

---

<a name="dockerfileVolume"> </a>
## dockerfileVolume

### predicate
docker:dockerfileVolume

### docker inspect value
VOLUME

### Domain
[Dockerfile](#Dockerfile)

### Range
literal (string)

### Examples
```
```

---

<a name="dockerfileWorkDir"> </a>
## dockerfileWorkDir

### predicate
docker:dockerfileWorkDir

### docker inspect value
WORKDIR

### Domain
[Dockerfile](#Dockerfile)

### Range
literal (string)

### Examples
```
```

---

<a name="dockerVersion"> </a>
## dockerVersion

### predicate
docker:dockerVersion

### docker inspect value
"DockerVersion"

### Domain
[Image](#Image)

### Range
literal (string)

### Examples
```
```

---

<a name="domainName"> </a>
## domainName

### predicate
docker:domainName

### docker inspect value
"Domainname"

### Domain
[DockerConfig](#DockerConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="driver"> </a>
## driver

### predicate
docker:driver

### docker inspect value
"Driver"

### Domain
[Mount](#Mount)

### Range
literal (string)

### Examples
```
```

---

<a name="endpointID"> </a>
## endpointID

### predicate
docker:endpointID

### docker inspect value
"EndpointID"

### Domain
[Network](#Network)

### Range
literal (string)

### Examples
```
```

---

<a name="endpointID"> </a>
## endpointID

### predicate
docker:endpointID

### docker inspect value
"EndpointID"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (string)

### Examples
```
```

---

<a name="entrypoint"> </a>
## entrypoint

### predicate
docker:entrypoint

### docker inspect value
"Entrypoint"

### Domain
[DockerConfig](#DockerConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="env"> </a>
## env

### predicate
docker:env

### docker inspect value
Env

### Domain
[DockerConfig](#DockerConfig)

### Range


### Examples
```
```

---

<a name="execIDs"> </a>
## execIDs

### predicate
docker:execIDs

### docker inspect value
"ExecIDs"

### Domain
[Container](#Container)

### Range
literal (string)

### Examples
```
```

---

<a name="ExitCode"> </a>
## ExitCode

### predicate
docker:exitCode

### docker inspect value
"ExitCode"

### Domain
[State](#State)

### Range
literal (string)

### Examples
```
```

---

<a name="extraHosts"> </a>
## extraHosts

### predicate
docker:extraHosts

### docker inspect value
"ExtraHosts"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="FinishedAt"> </a>
## FinishedAt

### predicate
docker:finishedAt

### docker inspect value
"FinishedAt"

### Domain
[State](#State)

### Range
literal (date)

### Examples
```
```

---

<a name="gateway"> </a>
## gateway

### predicate
docker:gateway

### docker inspect value
"Gateway"

### Domain
[Network](#Network)

### Range
literal (string)

### Examples
```
```

---

<a name="gateway"> </a>
## gateway

### predicate
docker:gateway

### docker inspect value
"Gateway"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (string)

### Examples
```
```

---

<a name="globalIPv6Address"> </a>
## globalIPv6Address

### predicate
docker:globalIPv6Address

### docker inspect value
"GlobalIPv6Address"

### Domain
[Network](#Network)

### Range
literal (string)

### Examples
```
```

---

<a name="globalIPv6Address"> </a>
## globalIPv6Address

### predicate
docker:globalIPv6Address

### docker inspect value
"GlobalIPv6Address"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (string)

### Examples
```
```

---

<a name="globalIPv6PrefixLen"> </a>
## globalIPv6PrefixLen

### predicate
docker:globalIPv6PrefixLen

### docker inspect value
"GlobalIPv6PrefixLen"

### Domain
[Network](#Network)

### Range
literal (number)

### Examples
```
```

---

<a name="globalIPv6PrefixLen"> </a>
## globalIPv6PrefixLen

### predicate
docker:globalIPv6PrefixLen

### docker inspect value
"GlobalIPv6PrefixLen"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (number)

### Examples
```
```

---

<a name="graphDriverData"> </a>
## graphDriverData

### predicate
docker:graphDriverData

### docker inspect value
"Data"

### Domain
[GraphDriver](#GraphDriver)

### Range
literal (string)

### Examples
```
```

---

<a name="graphDriverName"> </a>
## graphDriverName

### predicate
docker:graphDriverName

### docker inspect value
"Name"

### Domain
[GraphDriver](#GraphDriver)

### Range
literal (string)

### Examples
```
```

---

<a name="groupAdd"> </a>
## groupAdd

### predicate
docker:groupAdd

### docker inspect value
"GroupAdd"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="hairpinMode"> </a>
## hairpinMode

### predicate
docker:hairpinMode

### docker inspect value
"HairpinMode"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (boolean)

### Examples
```
```

---

<a name="hostName"> </a>
## hostName

### predicate
docker:hostName

### docker inspect value
"Hostname"

### Domain
[DockerConfig](#DockerConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="hostnamePath"> </a>
## hostnamePath

### predicate
docker:hostnamePath

### docker inspect value
"HostnamePath"

### Domain
[Container](#Container)

### Range
literal (string)

### Examples
```
```

---

<a name="hostsPath"> </a>
## hostsPath

### predicate
docker:hostsPath

### docker inspect value
"HostsPath"

### Domain
[Container](#Container)

### Range
literal (string)

### Examples
```
```

---

<a name="id"> </a>
## id

### predicate
docker:id

#### owl:sublcass of
dct:title

### docker inspect value
"Id"

### Domain
[Image](#Image)
[Container](#Container)

### Range
literal (string)

### Examples
```
```

---

<a name="intstructionCopy"> </a>
## intstructionCopy

### predicate
docker:intstructionCopy

### docker inspect value
COPY

### Domain
[Dockerfile](#Dockerfile)

### Range
literal (string)

### Examples
```
```

---

<a name="iOMaximumBandwidth"> </a>
## iOMaximumBandwidth

### predicate
docker:iOMaximumBandwidth

### docker inspect value
"IOMaximumBandwidth"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="iOMaximumIOps"> </a>
## iOMaximumIOps

### predicate
docker:iOMaximumIOps

### docker inspect value
"IOMaximumIOps"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="iPAddress"> </a>
## iPAddress

### predicate
docker:iPAddress

### docker inspect value
"IPAddress"

### Domain
[Network](#Network)

### Range
literal (string)

### Examples
```
```

---

<a name="iPAddress"> </a>
## iPAddress

### predicate
docker:iPAddress

### docker inspect value
"IPAddress"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (string)

### Examples
```
```

---

<a name="ipamConfig"> </a>
## ipamConfig

### predicate
docker:ipamConfig

### docker inspect value
"IPAMConfig"

### Domain
[Network](#Network)

### Range
literal (string)

### Examples
```
```

---

<a name="ipcMode"> </a>
## ipcMode

### predicate
docker:ipcMode

### docker inspect value
"IpcMode"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="iPPrefixLen"> </a>
## iPPrefixLen

### predicate
docker:iPPrefixLen

### docker inspect value
"IPPrefixLen"

### Domain
[Network](#Network)

### Range
literal (number)

### Examples
```
```

---

<a name="iPPrefixLen"> </a>
## iPPrefixLen

### predicate
docker:iPPrefixLen

### docker inspect value
"IPPrefixLen"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (number)

### Examples
```
```

---

<a name="iPv6Gateway"> </a>
## iPv6Gateway

### predicate
docker:iPv6Gateway

### docker inspect value
"IPv6Gateway"

### Domain
[Network](#Network)

### Range
literal (string)

### Examples
```
```

---

<a name="iPv6Gateway"> </a>
## iPv6Gateway

### predicate
docker:iPv6Gateway

### docker inspect value
"IPv6Gateway"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (string)

### Examples
```
```

---

<a name="isolation"> </a>
## isolation

### predicate
docker:isolation

### docker inspect value
"Isolation"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="kernelMemory"> </a>
## kernelMemory

### predicate
docker:kernelMemory

### docker inspect value
"KernelMemory"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="label"> </a>
## label

### predicate
docker:label

### docker inspect value
"Labels"

### Domain
[(1-*) DockerConfig](#(1-*) DockerConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="layer"> </a>
## layer

### predicate
docker:layer

### docker inspect value
"Layers"

### Domain
[(1-*) RootFS](#(1-*) RootFS)

### Range
literal (string)

### Examples
```
```

---

<a name="linkLocalIPv6Address"> </a>
## linkLocalIPv6Address

### predicate
docker:linkLocalIPv6Address

### docker inspect value
"LinkLocalIPv6Address"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (string)

### Examples
```
```

---

<a name="linkLocalIPv6PrefixLen"> </a>
## linkLocalIPv6PrefixLen

### predicate
docker:linkLocalIPv6PrefixLen

### docker inspect value
"linkLocalIPv6PrefixLen"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (number)

### Examples
```
```

---

<a name="links"> </a>
## links

### predicate
docker:links

### docker inspect value
"Links"

### Domain
[Network](#Network)

### Range
literal (string)

### Examples
```
```

---

<a name="logPath"> </a>
## logPath

### predicate
docker:logPath

### docker inspect value
"LogPath"

### Domain
[Container](#Container)

### Range
literal (string)

### Examples
```
```

---

<a name="logType"> </a>
## logType

### predicate
docker:logType

### docker inspect value
"Type"

### Domain
[LogConfig](#LogConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="macAddress"> </a>
## macAddress

### predicate
docker:macAddress

### docker inspect value
"MacAddress"

### Domain
[Network](#Network)

### Range
literal (string)

### Examples
```
```

---

<a name="macAddress"> </a>
## macAddress

### predicate
docker:macAddress

### docker inspect value
"MacAddress"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (string)

### Examples
```
```

---

<a name="maximumRetryCount"> </a>
## maximumRetryCount

### predicate
docker:maximumRetryCount

### docker inspect value
"MaximumRetryCount"

### Domain
[RestartPolicy](#RestartPolicy)

### Range
literal (number)

### Examples
```
```

---

<a name="memory"> </a>
## memory

### predicate
docker:memory

### docker inspect value
"Memory"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="memoryReservation"> </a>
## memoryReservation

### predicate
docker:memoryReservation

### docker inspect value
"MemoryReservation"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="memorySwap"> </a>
## memorySwap

### predicate
docker:memorySwap

### docker inspect value
"MemorySwap"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="memorySwappiness"> </a>
## memorySwappiness

### predicate
docker:memorySwappiness

### docker inspect value
"MemorySwappiness"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="mode"> </a>
## mode

### predicate
docker:mode

### docker inspect value
"Mode"

### Domain
[Mount](#Mount)

### Range
literal (string)

### Examples
```
```

---

<a name="mountLabel"> </a>
## mountLabel

### predicate
docker:mountLabel

### docker inspect value
"MountLabel"

### Domain
[Container](#Container)

### Range
literal (string)

### Examples
```
```

---

<a name="name"> </a>
## name

### predicate
docker:name

#### owl:subclass of
dct:title

### docker inspect value
"Name"

### Domain
[Container](#Container)
[Mount](#Mount)
[RestartPolicy](#RestartPolicy)
[Network](#Network)

### Range
literal (string)

### Examples
```
```

---

<a name="nanoCpus"> </a>
## nanoCpus

### predicate
docker:nanoCpus

### docker inspect value
"NanoCpus"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="networkID"> </a>
## networkID

### predicate
docker:networkID

### docker inspect value
"NetworkID"

### Domain
[Network](#Network)

### Range
literal (string)

### Examples
```
```

---

<a name="networkMode"> </a>
## networkMode

### predicate
docker:networkMode

### docker inspect value
"NetworkMode"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="onBuild"> </a>
## onBuild

### predicate
docker:onBuild

### docker inspect value
"onBuild"

### Domain
[DockerConfig](#DockerConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="oomKillDisable"> </a>
## oomKillDisable

### predicate
docker:oomKillDisable

### docker inspect value
"OomKillDisable"

### Domain
[HostConfig](#HostConfig)

### Range
literal (boolean)

### Examples
```
```

---

<a name="OOMKilled"> </a>
## OOMKilled

### predicate
docker:oomKilled

### docker inspect value
"OOMKilled"

### Domain
[State](#State)

### Range
literal (boolean)

### Examples
```
```

---

<a name="oomScoreAdj"> </a>
## oomScoreAdj

### predicate
docker:oomScoreAdj

### docker inspect value
"OomScoreAdj"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="openStdin"> </a>
## openStdin

### predicate
docker:openStdin

### docker inspect value
"OpenStdin"

### Domain
[DockerConfig](#DockerConfig)

### Range
literal (boolean)

### Examples
```
```

---

<a name="os"> </a>
## os

### predicate
docker:os

### docker inspect value
"Os"

### Domain
[Image](#Image)

### Range
literal (string)

### Examples
```
```

---

<a name="parent"> </a>
## parent

### predicate
docker:parent

### docker inspect value
"Parent"

### Domain
[Image](#Image)

### Range
literal (string)

### Examples
```
```

---

<a name="path"> </a>
## path

### predicate
docker:path

### docker inspect value
"Path"

### Domain
[Container](#Container)

### Range
literal (string)

### Examples
```
```

---

<a name="Paused"> </a>
## Paused

### predicate
docker:paused

### docker inspect value
"Paused"

### Domain
[State](#State)

### Range
literal (boolean)

### Examples
```
```

---

<a name="Pid"> </a>
## Pid

### predicate
docker:pid

### docker inspect value
"Pid"

### Domain
[State](#State)

### Range
literal (number)

### Examples
```
```

---

<a name="pidMode"> </a>
## pidMode

### predicate
docker:pidMode

### docker inspect value
"PidMode"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="pidsLimit"> </a>
## pidsLimit

### predicate
docker:pidsLimit

### docker inspect value
"PidsLimit"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---


<a name="privileged"> </a>
## privileged

### predicate
docker:privileged

### docker inspect value
"Privileged"

### Domain
[HostConfig](#HostConfig)

### Range
literal (boolean)

### Examples
```
```

---

<a name="processLabel"> </a>
## processLabel

### predicate
docker:processLabel

### docker inspect value
"ProcessLabel"

### Domain
[Container](#Container)

### Range
literal (string)

### Examples
```
```

---

<a name="propagation"> </a>
## propagation

### predicate
docker:propagation

### docker inspect value
"Propagation"

### Domain
[Mount](#Mount)

### Range
literal (string)

### Examples
```
```

---

<a name="publishedAllPorts"> </a>
## publishedAllPorts

### predicate
docker:publishedAllPorts

### docker inspect value
"PublishAllPorts"

### Domain
[HostConfig](#HostConfig)

### Range
literal (boolean)

### Examples
```
```

---

<a name="readonlyRootfs"> </a>
## readonlyRootfs

### predicate
docker:readonlyRootfs

### docker inspect value
"ReadonlyRootfs"

### Domain
[HostConfig](#HostConfig)

### Range
literal (boolean)

### Examples
```
```

---

<a name="resolveConfPath"> </a>
## resolveConfPath

### predicate
docker:resolveConfPath

### docker inspect value
"ResolvConfPath"

### Domain
[Container](#Container)

### Range
literal (string)

### Examples
```
```

---

<a name="restartCount"> </a>
## restartCount

### predicate
docker:restartCount

### docker inspect value
"RestartCount"

### Domain
[Container](#Container)

### Range
literal (number)

### Examples
```
```

---

<a name="Restarting"> </a>
## Restarting

### predicate
docker:restarting

### docker inspect value
"Restarting"

### Domain
[State](#State)

### Range
literal (boolean)

### Examples
```
```

---

<a name="rootFSType"> </a>
## rootFSType

### predicate
docker:rootFSType

### docker inspect value
"Type"

### Domain
[RootFS](#RootFS)

### Range
literal (string)

### Examples
```
```

---

<a name="Running"> </a>
## Running

### predicate
docker:running

### docker inspect value
"Running"

### Domain
[State](#State)

### Range
literal (boolean)

### Examples
```
```

---

<a name="runtime"> </a>
## runtime

### predicate
docker:runtime

### docker inspect value
"Runtime"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="rw"> </a>
## rw

### predicate
docker:rw

### docker inspect value
"RW"

### Domain
[Mount](#Mount)

### Range
literal (boolean)

### Examples
```
```

---

<a name="sandboxID"> </a>
## sandboxID

### predicate
docker:sandboxID

### docker inspect value
"SandboxID"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (string)

### Examples
```
```

---

<a name="sandboxKey"> </a>
## sandboxKey

### predicate
docker:sandboxKey

### docker inspect value
"SandboxKey"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (string)

### Examples
```
```

---

<a name="secondaryIPAddresses"> </a>
## secondaryIPAddresses

### predicate
docker:secondaryIPAddresses

### docker inspect value
"SecondaryIPAddresses"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (string)

### Examples
```
```

---

<a name="secondaryIPv6Addresses"> </a>
## secondaryIPv6Addresses

### predicate
docker:secondaryIPv6Addresses

### docker inspect value
"SecondaryIPv6Addresses"

### Domain
[NetworkSetting](#NetworkSetting)

### Range
literal (string)

### Examples
```
```

---

<a name="securityOpt"> </a>
## securityOpt

### predicate
docker:securityOpt

### docker inspect value
"SecurityOpt"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="shmSize"> </a>
## shmSize

### predicate
docker:shmSize

### docker inspect value
"ShmSize"

### Domain
[HostConfig](#HostConfig)

### Range
literal (number)

### Examples
```
```

---

<a name="size"> </a>
## size

### predicate
docker:size

### docker inspect value
"Size"

### Domain
[Image](#Image)

### Range
literal (number)

### Examples
```
```

---

<a name="source"> </a>
## source

### predicate
docker:source

#### subclass of
dct:source

### docker inspect value
"Source"

### Domain
[Mount](#Mount)

### Range
literal (string)

### Examples
```
```

---

<a name="StartedAt"> </a>
## StartedAt

### predicate
docker:startedAt

### docker inspect value
"StartedAt"

### Domain
[State](#State)

### Range
literal (date)

### Examples
```
```

---

<a name="Status"> </a>
## Status

### predicate
docker:status

### docker inspect value
"Status"

### Domain
[State](#State)

### Range
literal (string)

### Examples
```
```

---

<a name="tags"> </a>
## tags

### predicate
docker:tags

### docker inspect value
"RepoTags"

### Domain
[(1-*) Image](#(1-*) Image)

### Range
literal (string)

### Examples
```
```

---

<a name="tty"> </a>
## tty
Attach standard streams to a TTY, including stdin if it is not closed.

### predicate
docker:tty

### docker inspect value
"Tty"

### Domain
[DockerConfig](#DockerConfig)

### Range
literal (boolean)

### Examples
```
```

---

<a name="ulimits"> </a>
## ulimits

### predicate
docker:ulimits

### docker inspect value
"Ulimits"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="user"> </a>
## user

### predicate
docker:user

### docker inspect value
"User"

### Domain
[DockerConfig](#DockerConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="usernsMode"> </a>
## usernsMode

### predicate
docker:usernsMode

### docker inspect value
"UsernsMode"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="utsMode"> </a>
## utsMode

### predicate
docker:utsMode

### docker inspect value
"UTSMode"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---

<a name="virtualSize"> </a>
## virtualSize

### predicate
docker:virtualSize

### docker inspect value
"VirtualSize"

### Domain
[Image](#Image)

### Range
literal (number)

### Examples
```
```

---

<a name="volumeDriver"> </a>
## volumeDriver

### predicate
docker:volumeDriver

### docker inspect value
"VolumeDrive"

### Domain
[HostConfig](#HostConfig)

### Range
literal (string)

### Examples
```
```

---


<a name="workingDir"> </a>
## workingDir

### predicate
docker:workingDir

### docker inspect value
"WorkingDir"

### Domain
[DockerConfig](#DockerConfig)

### Range
literal (string)

### Examples
```
```

---
---

# Relations
<a name="blockIO"> </a>
## blockIO
Describes the blockIO for either a [Config](#Config) or a [HostConfig](#HostConfig).

### predicate
[docker](#docker):[blockIO](#blockIO)

### docker inspect value
BlockIO

### domain
[Config](#Config)
U
[HostConfig](#HostConfig)

### range
[BlockIO](#BlockIO)

---
<a name="cpu"> </a>
## cpu
Describes the CPU for either a [Config](#Config) or a [HostConfig](#HostConfig).

### predicate
[docker](#docker):[cpu](#cpu)

### docker inspect value
Cpu

### domain
[Config](#Config)
U
[HostConfig](#HostConfig)

### range
[CPU](#CPU)

---
<a name="config"> </a>
## config
Describes the configuration for either a [Container](#Container) or an [Image](#Image).

### predicate
[docker](#docker):[config](#config)

### docker inspect value
Config

### domain
[Container](#Container)
U
[Image](#Image)

### range
[Config](#Config)

---
<a name="dockerfile"> </a>
## dockerfile
Indicates the dockerfile from which an image was build.

### predicate
[docker](#docker):[dockerfile](#dockerfile)

### docker inspect value
Dockerfile

### domain
[Image](#Image)

### range
Dockerfile

---
<a name="graphDriver"> </a>
## graphDriver
The graph driver for an [Image](#Image).

### predicate
[docker](#docker):[graphDriver](#graphDriver)

### docker inspect value
GraphDriver

### domain
[Image](#Image)

### range
[GraphDriver](#GraphDriver)

---
<a name="hostConfig"> </a>
## hostConfig
Describes the network settings for an image or a container.

### predicate
[docker](#docker):[hostConfig](#hostConfig)

### docker inspect value
HostConfig

### domain
[Container](#Container)
U
[Image](#Image)

### range
[HostConfig](#HostConfig)

---
<a name="hostMapping"> </a>
## hostMapping
Describes the mapping to other running conainters for a given [NetworkSetting](#NetworkSetting).

### predicate
[docker](#docker):[hostMapping](#hostMapping)

### docker inspect value
HostMapping

### domain
[NetworkSetting](#NetworkSetting)

### range
[HostMapping](#HostMapping)

---
<a name="logConfig"> </a>
## logConfig
Describes how the logs are handled for a given [HostConfig](#HostConfig)

### predicate
[docker](#docker):[logConfig](#logConfig)

### docker inspect value
LogConfig

### domain
[HostConfig](#HostConfig)

### range
[LogConfig](#LogConfig)

---
<a name="mounts"> </a>
## mounts
Describes the mounts for a given [Container](#Container).

### predicate
[docker](#docker):[mounts](#mounts)

### docker inspect value
Mounts

### domain
[Container](#Container)

### range
[Mount](#Mount)

---
<a name="network"> </a>
## network
Links a [NetworkSettings](#NetworkSettings) with an actual [Network](#Network).

### predicate
[docker](#docker):[network](#network)

### docker inspect value
Network

### domain
[NetworkSettings](#NetworkSettings)

### range
[Network](#Network)

---
<a name="networkSettings"> </a>
## networkSettings
Describes the [NetworkSettings](#NetworkSettings) for a given [Container](#Container).

### predicate
[docker](#docker):[networkSettings](#networkSettings)

### docker inspect value
NetworkSettings

### domain
[Container](#Container)

### range
[NetworkSettings](#NetworkSettings)

---
<a name="repoDigest"> </a>
## repoDigest
Describes the repository digest (how it came to be) for a given [Image](#Image).

### predicate
[docker](#docker):[repoDigest](#repoDigest)

### docker inspect value
RepoDigest

### domain
[Image](#Image)

### range
[RepoDigest](#RepoDigest)

---
<a name="repoTags"> </a>
## repoTags
Describes the tags for a given [Image](#Image).

### predicate
[docker](#docker):[repoTags](#repoTags)

### docker inspect value
RepoTags

### domain
[Image](#Image)

### range
[RepoTags](#RepoTags)

---
<a name="restartPolicy"> </a>
## restartPolicy
Links to the [RestartPolicy](#RestartPolicy) for a [HostConfig](#HostConfig).

### predicate
[docker](#docker):[restartPolicy](#restartPolicy)

### docker inspect value
RestartPolicy

### domain
[HostConfig](#HostConfig)

### range
[RestartPolicy](#RestartPolicy)

---
<a name="rootFS"> </a>
## rootFS
Describes the filesystem for a given [Image](#Image).

### predicate
[docker](#docker):[rootFS](#rootFS)

### docker inspect value
RootFS

### domain
[Image](#Image)

### range
[RootFS](#RootFS)

---
<a name="state"> </a>
## state
Links to the state of a [Container](#Container) or an [Image](#Image).

### predicate
[docker](#docker):[state](#state)

### docker inspect value
State

### domain
[Container](#Container)
U
[Image](#Image)

### range
[State](#State)

---




@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
----------------------------------------------------------------------
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

# Docker Inspect Keys

The keys listed here are the ones that will be returned from the docker ecosystem (ie docker inspect, ....).

<a name="AliasesINSPECT"> </a>
## Aliases
[docker](#docker):[aliases](#aliases)

<a name="AppArmorProfileINSPECT"> </a>
## AppArmorProfile
[docker](#docker):[appArmorProfile](#appArmorProfile)

<a name="ArchitectureINSPECT"> </a>
## Architecture
[docker](#docker):[architecture](#architecture)

<a name="ArgsINSPECT"> </a>
## args
[docker](#docker):[args](#args)

<a name="ArgsEscapedINSPECT"> </a>
## argsescaped
[docker](#docker):[argsescaped](#argsescaped)

<a name="AttachStderrINSPECT"> </a>
## attachstderr
[docker](#docker):[attachstderr](#attachstderr)

<a name="AttachStdinINSPECT"> </a>
## attachstdin
[docker](#docker):[attachstdin](#attachstdin)

<a name="AttachStdoutINSPECT"> </a>
## attachstdout
[docker](#docker):[attachstdout](#attachstdout)

<a name="AuthorINSPECT"> </a>
## author
[docker](#docker):[author](#author)

<a name="AutoRemoveINSPECT"> </a>
## autoremove
[docker](#docker):[autoremove](#autoremove)

<a name="BindsINSPECT"> </a>
##binds
[docker](#docker):[binds](#binds)

<a name="BlkioDeviceReadBpsINSPECT"> </a>
##blkiodevicereadbps
[docker](#docker):[blkiodevicereadbps](#blkiodevicereadbps)

<a name="BlkioDeviceReadIOpsINSPECT"> </a>
##blkiodevicereadiops
[docker](#docker):[blkiodevicereadiops](#blkiodevicereadiops)

<a name="BlkioDeviceWriteBpsINSPECT"> </a>
##blkiodevicewritebps
[docker](#docker):[blkiodevicewritebps](#blkiodevicewritebps)

<a name="BlkioDeviceWriteIOpsINSPECT"> </a>
##blkiodevicewriteiops
[docker](#docker):[blkiodevicewriteiops](#blkiodevicewriteiops)

<a name="BlkioWeightINSPECT"> </a>
##blkioweight
[docker](#docker):[blkioweight](#blkioweight)

<a name="BlkioWeightDeviceINSPECT"> </a>
##blkioweightdevice
[docker](#docker):[blkioweightdevice](#blkioweightdevice)

<a name="BridgeINSPECT"> </a>
##bridge
[docker](#docker):[bridge](#bridge)

<a name="CapAddINSPECT"> </a>
##capadd
[docker](#docker):[capadd](#capadd)

<a name="CapDropINSPECT"> </a>
##capdrop
[docker](#docker):[capdrop](#capdrop)

<a name="CgroupINSPECT"> </a>
##cgroup
[docker](#docker):[cgroup](#cgroup)

<a name="CgroupParentINSPECT"> </a>
##cgroupparent
[docker](#docker):[cgroupparent](#cgroupparent)

<a name="CmdINSPECT"> </a>
##cmd
[docker](#docker):[cmd](#cmd)

<a name="CommentINSPECT"> </a>
##comment
[docker](#docker):[comment](#comment)

<a name="ConfigINSPECT"> </a>
##config
[docker](#docker):[config](#config)

<a name="ConfigINSPECT"> </a>
##config
[docker](#docker):[config](#config)

<a name="ConsoleSizeINSPECT"> </a>
##consolesize
[docker](#docker):[consolesize](#consolesize)

<a name="ContainerINSPECT"> </a>
##container
[docker](#docker):[container](#container)

<a name="ContainerIDFileINSPECT"> </a>
##containeridfile
[docker](#docker):[containeridfile](#containeridfile)

<a name="CpuCountINSPECT"> </a>
##cpucount
[docker](#docker):[cpucount](#cpucount)

<a name="CpuPercentINSPECT"> </a>
##cpupercent
[docker](#docker):[cpupercent](#cpupercent)

<a name="CpuPeriodINSPECT"> </a>
##cpuperiod
[docker](#docker):[cpuperiod](#cpuperiod)

<a name="CpuQuotaINSPECT"> </a>
##cpuquota
[docker](#docker):[cpuquota](#cpuquota)

<a name="CpuRealtimePeriodINSPECT"> </a>
##cpurealtimeperiod
[docker](#docker):[cpurealtimeperiod](#cpurealtimeperiod)

<a name="CpuRealtimeRuntimeINSPECT"> </a>
##cpurealtimeruntime
[docker](#docker):[cpurealtimeruntime](#cpurealtimeruntime)

<a name="CpusetCpusINSPECT"> </a>
##cpusetcpus
[docker](#docker):[cpusetcpus](#cpusetcpus)

<a name="CpusetMemsINSPECT"> </a>
##cpusetmems
[docker](#docker):[cpusetmems](#cpusetmems)

<a name="CpuSharesINSPECT"> </a>
##cpushares
[docker](#docker):[cpushares](#cpushares)

<a name="CreatedINSPECT"> </a>
##created
[docker](#docker):[created](#created)

<a name="CreatedINSPECT"> </a>
##created
[docker](#docker):[created](#created)

<a name="DataINSPECT"> </a>
##data
[docker](#docker):[data](#data)

<a name="DeadINSPECT"> </a>
##dead
[docker](#docker):[dead](#dead)

<a name="DestinationINSPECT"> </a>
##destination
[docker](#docker):[destination](#destination)

<a name="DeviceCgroupRulesINSPECT"> </a>
##devicecgrouprules
[docker](#docker):[devicecgrouprules](#devicecgrouprules)

<a name="DevicesINSPECT"> </a>
##devices
[docker](#docker):[devices](#devices)

<a name="DiskQuotaINSPECT"> </a>
##diskquota
[docker](#docker):[diskquota](#diskquota)

<a name="DnsINSPECT"> </a>
##dns
[docker](#docker):[dns](#dns)

<a name="DnsOptionsINSPECT"> </a>
##dnsoptions
[docker](#docker):[dnsoptions](#dnsoptions)

<a name="DnsSearchINSPECT"> </a>
##dnssearch
[docker](#docker):[dnssearch](#dnssearch)

<a name="DockerVersionINSPECT"> </a>
##dockerversion
[docker](#docker):[dockerversion](#dockerversion)

<a name="DomainnameINSPECT"> </a>
##domainname
[docker](#docker):[domainname](#domainname)

<a name="DriverINSPECT"> </a>
##driver
[docker](#docker):[driver](#driver)

<a name="EndpointIDINSPECT"> </a>
##endpointid
[docker](#docker):[endpointid](#endpointid)

<a name="EndpointIDINSPECT"> </a>
##endpointid
[docker](#docker):[endpointid](#endpointid)

<a name="EntrypointINSPECT"> </a>
##entrypoint
[docker](#docker):[entrypoint](#entrypoint)

<a name="ExecIDsINSPECT"> </a>
##execids
[docker](#docker):[execids](#execids)

<a name="ExitCodeINSPECT"> </a>
##exitcode
[docker](#docker):[exitcode](#exitcode)

<a name="ExtraHostsINSPECT"> </a>
##extrahosts
[docker](#docker):[extrahosts](#extrahosts)

<a name="FinishedAtINSPECT"> </a>
##finishedat
[docker](#docker):[finishedat](#finishedat)

<a name="GatewayINSPECT"> </a>
##gateway
[docker](#docker):[gateway](#gateway)

<a name="GatewayINSPECT"> </a>
##gateway
[docker](#docker):[gateway](#gateway)

<a name="GlobalIPv6AddressINSPECT"> </a>
##globalipv6address
[docker](#docker):[globalipv6address](#globalipv6address)

<a name="GlobalIPv6AddressINSPECT"> </a>
##globalipv6address
[docker](#docker):[globalipv6address](#globalipv6address)

<a name="GlobalIPv6PrefixLenINSPECT"> </a>
##globalipv6prefixlen
[docker](#docker):[globalipv6prefixlen](#globalipv6prefixlen)

<a name="GlobalIPv6PrefixLenINSPECT"> </a>
##globalipv6prefixlen
[docker](#docker):[globalipv6prefixlen](#globalipv6prefixlen)

<a name="GraphDriverINSPECT"> </a>
##graphdriver
[docker](#docker):[graphdriver](#graphdriver)

<a name="GroupAddINSPECT"> </a>
##groupadd
[docker](#docker):[groupadd](#groupadd)

<a name="HairpinModeINSPECT"> </a>
##hairpinmode
[docker](#docker):[hairpinmode](#hairpinmode)

<a name="HostConfigINSPECT"> </a>
##hostconfig
[docker](#docker):[hostconfig](#hostconfig)

<a name="HostnameINSPECT"> </a>
##hostname
[docker](#docker):[hostname](#hostname)

<a name="HostnamePathINSPECT"> </a>
##hostnamepath
[docker](#docker):[hostnamepath](#hostnamepath)

<a name="HostsPathINSPECT"> </a>
##hostspath
[docker](#docker):[hostspath](#hostspath)

<a name="IdINSPECT"> </a>
##id
[docker](#docker):[id](#id)

<a name="IdINSPECT"> </a>
##id
[docker](#docker):[id](#id)

<a name="ImageINSPECT"> </a>
##image
[docker](#docker):[image](#image)

<a name="ImageINSPECT"> </a>
##image
[docker](#docker):[image](#image)

<a name="IOMaximumBandwidthINSPECT"> </a>
##iomaximumbandwidth
[docker](#docker):[iomaximumbandwidth](#iomaximumbandwidth)

<a name="IOMaximumIOpsINSPECT"> </a>
##iomaximumiops
[docker](#docker):[iomaximumiops](#iomaximumiops)

<a name="IPAddressINSPECT"> </a>
##ipaddress
[docker](#docker):[ipaddress](#ipaddress)

<a name="IPAddressINSPECT"> </a>
##ipaddress
[docker](#docker):[ipaddress](#ipaddress)

<a name="IPAMConfigINSPECT"> </a>
##ipamconfig
[docker](#docker):[ipamconfig](#ipamconfig)

<a name="IpcModeINSPECT"> </a>
##ipcmode
[docker](#docker):[ipcmode](#ipcmode)

<a name="IPPrefixLenINSPECT"> </a>
##ipprefixlen
[docker](#docker):[ipprefixlen](#ipprefixlen)

<a name="IPPrefixLenINSPECT"> </a>
##ipprefixlen
[docker](#docker):[ipprefixlen](#ipprefixlen)

<a name="IPv6GatewayINSPECT"> </a>
##ipv6gateway
[docker](#docker):[ipv6gateway](#ipv6gateway)

<a name="IPv6GatewayINSPECT"> </a>
##ipv6gateway
[docker](#docker):[ipv6gateway](#ipv6gateway)

<a name="IsolationINSPECT"> </a>
##isolation
[docker](#docker):[isolation](#isolation)

<a name="KernelMemoryINSPECT"> </a>
##kernelmemory
[docker](#docker):[kernelmemory](#kernelmemory)

<a name="LabelsINSPECT"> </a>
##labels
[docker](#docker):[labels](#labels)

<a name="LayersINSPECT"> </a>
##layers
[docker](#docker):[layers](#layers)

<a name="LinkLocalIPv6AddressINSPECT"> </a>
##linklocalipv6address
[docker](#docker):[linklocalipv6address](#linklocalipv6address)

<a name="LinksINSPECT"> </a>
##links
[docker](#docker):[links](#links)

<a name="LinksINSPECT"> </a>
##links
[docker](#docker):[links](#links)

<a name="literalINSPECT"> </a>
##literal
[docker](#docker):[literal](#literal)

<a name="LogConfigINSPECT"> </a>
##logconfig
[docker](#docker):[logconfig](#logconfig)

<a name="LogPathINSPECT"> </a>
##logpath
[docker](#docker):[logpath](#logpath)

<a name="MacAddressINSPECT"> </a>
##macaddress
[docker](#docker):[macaddress](#macaddress)

<a name="MacAddressINSPECT"> </a>
##macaddress
[docker](#docker):[macaddress](#macaddress)

<a name="MaximumRetryCountINSPECT"> </a>
##maximumretrycount
[docker](#docker):[maximumretrycount](#maximumretrycount)

<a name="MemoryINSPECT"> </a>
##memory
[docker](#docker):[memory](#memory)

<a name="MemoryReservationINSPECT"> </a>
##memoryreservation
[docker](#docker):[memoryreservation](#memoryreservation)

<a name="MemorySwapINSPECT"> </a>
##memoryswap
[docker](#docker):[memoryswap](#memoryswap)

<a name="MemorySwappinessINSPECT"> </a>
##memoryswappiness
[docker](#docker):[memoryswappiness](#memoryswappiness)

<a name="ModeINSPECT"> </a>
##mode
[docker](#docker):[mode](#mode)

<a name="MountLabelINSPECT"> </a>
##mountlabel
[docker](#docker):[mountlabel](#mountlabel)

<a name="MountsINSPECT"> </a>
##mounts
[docker](#docker):[mounts](#mounts)

<a name="NameINSPECT"> </a>
##name
[docker](#docker):[name](#name)

<a name="NameINSPECT"> </a>
##name
[docker](#docker):[name](#name)

<a name="NameINSPECT"> </a>
##name
[docker](#docker):[name](#name)

<a name="NameINSPECT"> </a>
##name
[docker](#docker):[name](#name)

<a name="NanoCpusINSPECT"> </a>
##nanocpus
[docker](#docker):[nanocpus](#nanocpus)

<a name="NetworkIDINSPECT"> </a>
##networkid
[docker](#docker):[networkid](#networkid)

<a name="NetworkModeINSPECT"> </a>
##networkmode
[docker](#docker):[networkmode](#networkmode)

<a name="NetworksINSPECT"> </a>
##networks
[docker](#docker):[networks](#networks)

<a name="NetworkSettingsINSPECT"> </a>
##networksettings
[docker](#docker):[networksettings](#networksettings)

<a name="OomKillDisableINSPECT"> </a>
##oomkilldisable
[docker](#docker):[oomkilldisable](#oomkilldisable)

<a name="OOMKilledINSPECT"> </a>
##oomkilled
[docker](#docker):[oomkilled](#oomkilled)

<a name="OomScoreAdjINSPECT"> </a>
##oomscoreadj
[docker](#docker):[oomscoreadj](#oomscoreadj)

<a name="OpenStdinINSPECT"> </a>
##openstdin
[docker](#docker):[openstdin](#openstdin)

<a name="OsINSPECT"> </a>
##os
[docker](#docker):[os](#os)

<a name="ParentINSPECT"> </a>
##parent
[docker](#docker):[parent](#parent)

<a name="PathINSPECT"> </a>
##path
[docker](#docker):[path](#path)

<a name="PausedINSPECT"> </a>
##paused
[docker](#docker):[paused](#paused)

<a name="PidINSPECT"> </a>
##pid
[docker](#docker):[pid](#pid)

<a name="PidModeINSPECT"> </a>
##pidmode
[docker](#docker):[pidmode](#pidmode)

<a name="PidsLimitINSPECT"> </a>
##pidslimit
[docker](#docker):[pidslimit](#pidslimit)

<a name="PortBindingsINSPECT"> </a>
##portbindings
[docker](#docker):[portbindings](#portbindings)

<a name="PortsINSPECT"> </a>
##ports
[docker](#docker):[ports](#ports)

<a name="PrivilegedINSPECT"> </a>
##privileged
[docker](#docker):[privileged](#privileged)

<a name="ProcessLabelINSPECT"> </a>
##processlabel
[docker](#docker):[processlabel](#processlabel)

<a name="PropagationINSPECT"> </a>
##propagation
[docker](#docker):[propagation](#propagation)

<a name="PublishAllPortsINSPECT"> </a>
##publishallports
[docker](#docker):[publishallports](#publishallports)

<a name="ReadonlyRootfsINSPECT"> </a>
##readonlyrootfs
[docker](#docker):[readonlyrootfs](#readonlyrootfs)

<a name="RepoDigestsINSPECT"> </a>
##repodigests
[docker](#docker):[repodigests](#repodigests)

<a name="RepoTagsINSPECT"> </a>
##repotags
[docker](#docker):[repotags](#repotags)

<a name="ResolvConfPathINSPECT"> </a>
##resolvconfpath
[docker](#docker):[resolvconfpath](#resolvconfpath)

<a name="RestartCountINSPECT"> </a>
##restartcount
[docker](#docker):[restartcount](#restartcount)

<a name="RestartingINSPECT"> </a>
##restarting
[docker](#docker):[restarting](#restarting)

<a name="RestartPoliciyINSPECT"> </a>
##restartpoliciy
[docker](#docker):[restartpoliciy](#restartpoliciy)

<a name="RunningINSPECT"> </a>
##running
[docker](#docker):[running](#running)

<a name="RuntimeINSPECT"> </a>
##runtime
[docker](#docker):[runtime](#runtime)

<a name="RWINSPECT"> </a>
##rw
[docker](#docker):[rw](#rw)

<a name="SandboxIDINSPECT"> </a>
##sandboxid
[docker](#docker):[sandboxid](#sandboxid)

<a name="SandboxKeyINSPECT"> </a>
##sandboxkey
[docker](#docker):[sandboxkey](#sandboxkey)

<a name="SecondaryIPAddressesINSPECT"> </a>
##secondaryipaddresses
[docker](#docker):[secondaryipaddresses](#secondaryipaddresses)

<a name="SecondaryIPv6AddressesINSPECT"> </a>
##secondaryipv6addresses
[docker](#docker):[secondaryipv6addresses](#secondaryipv6addresses)

<a name="SecurityOptINSPECT"> </a>
##securityopt
[docker](#docker):[securityopt](#securityopt)

<a name="ShmSizeINSPECT"> </a>
##shmsize
[docker](#docker):[shmsize](#shmsize)

<a name="SizeINSPECT"> </a>
##size
[docker](#docker):[size](#size)

<a name="SourceINSPECT"> </a>
##source
[docker](#docker):[source](#source)

<a name="StartedAtINSPECT"> </a>
##startedat
[docker](#docker):[startedat](#startedat)

<a name="StateINSPECT"> </a>
##state
[docker](#docker):[state](#state)

<a name="StatusINSPECT"> </a>
##status
[docker](#docker):[status](#status)

<a name="TtyINSPECT"> </a>
##tty
[docker](#docker):[tty](#tty)

<a name="TypeINSPECT"> </a>
##type
[docker](#docker):[type](#type)

<a name="TypeINSPECT"> </a>
##type
[docker](#docker):[type](#type)

<a name="UlimitsINSPECT"> </a>
##ulimits
[docker](#docker):[ulimits](#ulimits)

<a name="UserINSPECT"> </a>
##user
[docker](#docker):[user](#user)

<a name="UsernsModeINSPECT"> </a>
##usernsmode
[docker](#docker):[usernsmode](#usernsmode)

<a name="UTSModeINSPECT"> </a>
##utsmode
[docker](#docker):[utsmode](#utsmode)

<a name="VirtualSizeINSPECT"> </a>
##virtualsize
[docker](#docker):[virtualsize](#virtualsize)

<a name="VolumeDriveINSPECT"> </a>
##volumedrive
[docker](#docker):[volumedrive](#volumedrive)

<a name=WorkingDirINSPECT> </a>
## workingdir
[docker](#docker):[workingdir](#workingdir)

