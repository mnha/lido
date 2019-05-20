---
description: Event Place
---

# eventPlace \[Beginning of existence\]

### Description

#### LIDO

Place specification of the event.

#### MNHA

This element contains the follwing element:

* `place`

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:eventPlace>
    <lido:place>
        <lido:partOfPlace lido:polticalEntity="country">
            <lido:namePlaceSet>
                <lido:appellationValue>#Objets | Réf. géo. | [type=lieu de création ; level=1] (fr)</lido:appellationValue>
                <lido:appellationValue xml:lang="de">#Objets | Réf. géo. | [type=lieu de création ; level=1] (de)</lido:appellationValue>
                <lido:appellationValue xml:lang="en">#Objets | Réf. géo. | [type=lieu de création ; level=1] (en)</lido:appellationValue>
            </lido:namePlaceSet>
        <lido:partOfPlace lido:polticalEntity="city">
            <lido:namePlaceSet>
                <lido:appellationValue>#Objets | Réf. géo. | [type=lieu de création ; level=2] (fr)</lido:appellationValue>
                <lido:appellationValue xml:lang="de">#Objets | Réf. géo. | [type=lieu de création ; level=2] (de)</lido:appellationValue>
                <lido:appellationValue xml:lang="en">#Objets | Réf. géo. | [type=lieu de création ; level=2] (en)</lido:appellationValue>
            </lido:namePlaceSet>
        <lido:partOfPlace lido:polticalEntity="place">
            <lido:namePlaceSet>
                <lido:appellationValue>#Objets | Réf. géo. | [type=lieu de création ; level=3] (fr)</lido:appellationValue>
                <lido:appellationValue xml:lang="de">#Objets | Réf. géo. | [type=lieu de création ; level=3] (de)</lido:appellationValue>
                <lido:appellationValue xml:lang="en">#Objets | Réf. géo. | [type=lieu de création ; level=3] (en)</lido:appellationValue>
            </lido:namePlaceSet>
        </lido:partOfPlace>
        </lido:partOfPlace>
        </lido:partOfPlace>
    </place>
</lido:eventPlace>
```

