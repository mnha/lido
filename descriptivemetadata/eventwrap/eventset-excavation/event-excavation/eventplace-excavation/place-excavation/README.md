---
description: Place
---

# place \[Excavation\]

### Definition

#### LIDO

Contains structured identifying and indexing information for a geographical entity.

#### MNHA

This element contains the following element:

* `partOfPlace` \[Excavation\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:place>
    <lido:partOfPlace lido:politicalEntity="country">
        <lido:namePlaceSet>
            <lido:appellationValue>#Objets | Réf. géo. [type=lieu de trouvaille ; level 1] (fr)#</lido:appellationValue>
            <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu de trouvaille ; level 1] (de)#</lido:appellationValue>
            <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu de trouvaille ; level 1] (en)#</lido:appellationValue>
        </lido:namePlaceSet>
    </lido:partOfPlace>
    <lido:partOfPlace lido:politicalEntity="city">
        <lido:namePlaceSet>
            <lido:appellatioValue>#Objets | Réf. géo. [type=lieu de trouvaille ; level 2] (fr)#</lido:apppellationValue>
            <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu de trouvaille ; level 2] (de)#</lido:appellationValue>
            <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu de trouvaille ; level 2] (en)#</lido:appellationValue>
        </lido:namePlaceSet>
    </lido:partOfPlace>
    <lido:partOfPlace lido:politicalEntity="place">
        <lido:namePlaceSet>
            <lido:appellationValue>#Objets | Réf. géo. [type=lieu de trouvaille ; level 3] (fr)#</lido:appellationValue>
            <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu de trouvaille ; level 3] (de)#</lido:appelationValue>
            <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu de trouvaille ; level 3] (en)#</lido:appellationValue>
        </lido:namePlaceSet>
    </lido:partOfPlace>
</lido:place>
```

