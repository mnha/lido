---
description: Event Set
---

# eventSet \[Excavation\]

### Definition

#### LIDO

Wrapper for the display and index elements for events \[e.g. creation, find, and use\), in which the object participated.

#### MNHA

This element contains the following element:

* `event` \[Excavation\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:eventSet>
    <lido:event>
        <lido:eventType>
            <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">
                http://terminology.lido-schema.org/eventType/excavation
            </lido:conceptID>
            <lido:term>Fouille</lido:term>
            <lido:term xml:lang="de">Ausgrabung</lido:term>
            <lido:term xml:lang0"en">Excavation</lido:term>
        </lido:eventType>
        <lido:eventPlace>
            <lido:place>
                <lido:partOfplace lido:politicalEntity="country">
                    <lido:namePlaceSet>
                        <lido:appellationValue>#Objets | Réf. géo. [type=lieu de trouvaille ; level 1] (fr)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu de trouvaille ; level 1] (de)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu de trouvaille ; level 1] (en)#</lido:appellationValue>
                    </lido:namePlaceSet>
                </lido:partOfPlace>
                <lido:partOfplace lido:politicalEntity="city">
                    <lido:namePlaceSet>
                        <lido:appellationValue>#Objets | Réf. géo. [type=lieu de trouvaille ; level 2] (fr)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu de trouvaille ; level 2] (de)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu de trouvaille ; level 2] (en)#</lido:appellationValue>
                    </lido:namePlaceSet>
                </lido:partOfPlace>
                <lido:partOfplace lido:politicalEntity="place">
                    <lido:namePlaceSet>
                        <lido:appellationValue>#Objets | Réf. géo. [type=lieu de trouvaille ; level 3] (fr)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu de trouvaille ; level 3] (de)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu de trouvaille ; level 3] (en)#</lido:appellationValue>
                    </lido:namePlaceSet>
                </lido:partOfPlace>
            </lido:place>
        </lido:eventPlace>
    </lido:event>
</lido:eventSet>
```

