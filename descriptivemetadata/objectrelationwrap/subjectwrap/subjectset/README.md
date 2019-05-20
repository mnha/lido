---
description: Subject Set
---

# subjectSet

### Description

#### LIDO

Wrapper for display and index elements for one set of subject information.

#### MNHA

This element contains the following element:

* `subjectPlace`

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:subjectSet>
    <lido:subject>
        <lido:subjectPlace>
            <lido:place>
                <lido:partOfPlace lido:politicalEntity="country">
                    <lido:namePlaceSet>
                        <lido:appellationValue>#Objets | Réf. géo. | [type=lieu représenté ; level=1] (fr)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="de">#Objets | Réf. géo. | [type=lieu représenté ; level=1] (de)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="en">#Objets | Réf. géo. | [type=lieu représenté ; level=1] (en)#</lido:appellationValue>
                    </lido:namePlaceSet>
                <lido:partOfPlace lido:polticalEntity="city">
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
    </lido:subject>
</lido:subjectSet>
```

