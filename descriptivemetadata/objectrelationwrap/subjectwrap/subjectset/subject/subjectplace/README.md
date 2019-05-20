---
description: Subject Place Set
---

# subjectPlace

### Description

#### LIDO

A place depicted in or by an object/work, or what it is about, provided as display and index elements.

#### MNHA

This elements contains the following element:

* `place`

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:subjectPlace>
    <lido:place>
        <lido:partOfPlace politicalEntity="country">
            <lido:namePlaceSet>
                <lido:appellationValue>#Objets | Réf. géo. | [type=lieu représenté ; level=1] (fr)#</lido:appellationValue>
                <lido:appellationValue xml:lang="de">#Objets | Réf. géo. | [type=lieu représenté ; level=1] (de)#</lido:appellationValue>
                <lido:appellationValue xml:lang="en">#Objets | Réf. géo. | [type=lieu représenté ; level=1] (en)#</lido:appellationValue>
            </lido:namePlaceSet>
        <lido:partOfPlace politicalEntity="city">
            <lido:namePlaceSet>
                <lido:appellationValue>#Objets | Réf. géo. | [type=lieu représenté ; level=2] (fr)#</lido:appellationValue>
                <lido:appellationValue xml:lang="de">#Objets | Réf. géo. | [type=lieu représenté ; level=2] (de)#</lido:appellationValue>
                <lido:appellationValue xml:lang="en">#Objets | Réf. géo. | [type=lieu représenté ; level=2] (en)#</lido:appellationValue>
            </lido:namePlaceSet>
        <lido:partOfPlace politicalEntity="place">
            <lido:namePlaceSet>
                <lido:appellationValue>#Objets | Réf. géo. | [type=lieu représenté ; level=3] (fr)#</lido:appellationValue>
                <lido:appellationValue xml:lang="de">#Objets | Réf. géo. | [type=lieu représenté ; level=3] (de)#</lido:appellationValue>
                <lido:appellationValue xml:lang="en">#Objets | Réf. géo. | [type=lieu représenté ; level=3] (en)#</lido:appellationValue>
            </lido:namePlaceSet>
        </lido:partOfPlace>
        </lido:partOfPlace>
        </lido:partOfPlace>
    </lido:place>
</lido:subjectPlace>
```

