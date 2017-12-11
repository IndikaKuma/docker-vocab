# Docker-Compose Ontology

## Classes
[BuildConfig](#BuildConfig)
[DockerComposition](#DockerComposition)
[Service](#Service)

## Properties

## Relations

# Classes
<a name="BuildConfig"></a>
## BuildConfig

#### Description

#### Equivalent
none

#### Properties
| Predicate                             | OWL:sameAs       | Docker-Compose-File      | Type                   |   Arity |
| :---------------------------          | :--------------: | :----------------------: | :--------------------: | :-----: |
| [drc](#drc):[context](#context)       |                  | context                  | literal:string         |     1-1 |
| [drc](#drc):[dockerfile](#dockerfile) |                  | dockerfile               | literal:string         |     1-1 |
| [drc](#drc):[args](#args)             |                  | args                     | literal:string         |     1-1 |
| [drc](#drc):[labels](#labels)         |                  | labels                   | literal:string         |     1-1 |
| [drc](#drc):[network](#network)       |                  | network                  | literal:string         |     1-1 |
| [drc](#drc):[target](#target)         |                  | target                   | literal:string         |     1-1 |

#### Relations

##### Domain of

##### Range of 

#### Example
```
```

---

<a name="DockerComposition"></a>
## DockerComposition

#### Description

#### Equivalent
none

#### Properties
| Predicate                             | OWL:sameAs       | Docker-Compose-File      | Type                   |   Arity |
| :---------------------------          | :--------------: | :----------------------: | :--------------------: | :-----: |
| [dco](#dco):[version](#version)       |                  | version                  | literal:string         |     1-1 |
| [dco](#dco):[File](#File)             |                  | File                     | literal:string         |     1-1 |
| [dco](#dco):[Service](#Service)       |                  | Service                  | literal:string         |     1-1 |
| [dco](#dco):[hasService](#hasService) |                  | hasService               | literal:string         |     1-1 |
| [dct](#dct):[title](#title)           |                  | title                    | literal:string         |     1-1 |


#### Relations

##### Domain of

##### Range of 

#### Example
```
```

---

<a name="Service"></a>
## Service

#### Description

#### Equivalent
none

#### Properties
| Predicate                             | OWL:sameAs       | Docker-Compose-File      | Type                   |   Arity |
| :---------------------------          | :--------------: | :----------------------: | :--------------------: | :-----: |


#### Relations

##### Domain of

##### Range of 

#### Example
```
```

---
