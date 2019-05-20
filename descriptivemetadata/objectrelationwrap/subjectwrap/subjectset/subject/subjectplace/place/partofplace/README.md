---
description: Part of Geographical Entity
---

# partOfPlace

### Description

#### LIDO

Allows for indexing larger geographical entities.

#### MNHA

This elements contains the following element:

* `namePlaceSet`

### Attributes

**@politicalEntity**

This attribute contains the following default values:

`country` \| `city` \| `place`

### Example

```markup
<lido:partofPlace politcalEntity="country">
    <lido:namePlaceSet>
        <lido:appellationValue>#Objets | Réf. géo. | [type=lieu représenté ; level=1] (fr)</lido:appellationValue>
        <lido:appellationValue xml:lang="de">#Objets | Réf. géo. | [type=lieu représenté ; level=1] (de)</lido:appellationValue>
        <lido:appellationValue xml:lang="en">#Objets | Réf. géo. | [type=lieu représenté ; level=1] (en)</lido:appellationValue>
    </lido:namePlaceSet>
</lido:partofPlace>
```

