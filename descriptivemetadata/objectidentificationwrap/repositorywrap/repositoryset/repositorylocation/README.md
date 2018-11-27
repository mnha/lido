---
description: Location
---

# repositoryLocation

### Definition

#### LIDO

Location of the object, especially relevant for architecture and archaeological sites.

#### MNHA

This element contains the following elements:

* `placeID`
* `namePlaceSet`

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:repositoryLocation>
    <lido:placeID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier">
        #Location in museum (Link)#
    </lido:placeID>
    <lido:namePlaceSet>
        <lido:appellationValue>#Objets | Empl. actuel (Text) (fr)#</lido:appellationValue>
        <lido:appellationValue xml:lang="de">#Objets | Empl. actuel (Text) (de)#</lido:appellationValue>
        <lido:appellationValue xml:lang="en">#Objets | Empl. actuel (Text) (en)#</lido:appellationValue>
    </lido:namePlaceSet>
</lido:repositoryLocation>
```



