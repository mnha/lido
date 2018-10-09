---
description: Location
---

# repositoryLocation

### Definition

Location of the object, especially relevant for architecture and archaeological sites.

This element contains the following elements:

* placeID
* namePlaceSet

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:repositoryLocation>
    <lido:placeID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier">
        #Location in museum (Link)#
    </lido:placeID>
    <lido:namePlaceSet>
        <lido:appellationValue>#Location in museum (Text) (fr)#</lido:appellationValue>
        <lido:appellationValue xml:lang="de">#Location in museum (Text) (de)#</lido:appellationValue>
        <lido:appellationValue xml:lang="en">#Location in museum (Text) (en)#</lido:appellationValue>
    </lido:namePlaceSet>
</lido:repositoryLocation>
```



