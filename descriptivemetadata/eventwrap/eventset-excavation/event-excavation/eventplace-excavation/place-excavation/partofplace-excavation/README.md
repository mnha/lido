---
description: Part of Geographical Entity
---

# partOfPlace \[Excavation\]

### Definition

#### LIDO

Allows for indexing larger geographical entities.

#### MNHA

This element contains the following element:

* `namePlaceSet` \[Excavation\]

### Attributes

**@politicalEntity**

This attribute contains the following default values:

`country` \| `city` \| `place`

### Example

```markup
<lido:partOfPlace lido:politicalEntity="country">
    <lido:namePlaceSet>
        <lido:appellationValue>#Objets | Réf. géo. [type=lieu de trouvaille ; level 1] (fr)#</lido:appellationValue>
        <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu de trouvaille ; level 1] (de)#</lido:appellationValue>
        <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu de trouvaille ; level 1] (en)#</lido:appellationValue>
    </lido:namePlaceSet>
</lido:partOfPlace>
```

