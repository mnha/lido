---
description: Place
---

# place

### Description

#### LIDO

Contains structured identifying and indexing information for a geographical entity.

#### MNHA

This element contains the following element:

* `partOfPlace`

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:place>
    <lido:partOfPlace politicalEntity="country">
        <lido:placeNameSet>
            <lido:appellationValue>#Objets | Réf. géo. |[type=lieu représenté ; level=1] (fr)#</lido:appellationValue>
            <lido:appellationValue xml:lang="de">#Objets | Réf. géo. |[type=lieu représenté ; level=1] (de)#</lido:appellationValue>
            <lido:appellationValue xml:lang="en">#Objets | Réf. géo. |[type=lieu représenté ; level=1] (en)#</lido:appellationValue>
        </lido:namePlaceSet>
    <lido:partOfPlace politicalEntity="city">
        <lido:placeNameSet>
            <lido:appellationValue>#Objets | Réf. géo. |[type=lieu représenté ; level=2] (fr)#</lido:appellationValue>
            <lido:appellationValue xml:lang="de">#Objets | Réf. géo. |[type=lieu représenté ; level=2] (de)#</lido:appellationValue>
            <lido:appellationValue xml:lang="en">#Objets | Réf. géo. |[type=lieu représenté ; level=2] (en)#</lido:appellationValue>
        </lido:namePlaceSet>
    <lido:partOfPlace politicalEntity="place">
        <lido:placeNameSet>
            <lido:appellationValue>#Objets | Réf. géo. |[type=lieu représenté ; level=3] (fr)#</lido:appellationValue>
            <lido:appellationValue xml:lang="de">#Objets | Réf. géo. |[type=lieu représenté ; level=3] (de)#</lido:appellationValue>
            <lido:appellationValue xml:lang="en">#Objets | Réf. géo. |[type=lieu représenté ; level=3] (en)#</lido:appellationValue>
        </lido:namePlaceSet>
    </lido:partOfPlace>
    </lido:partOfPlace>
    </lido:partOfPlace>
</lido:place>
```

