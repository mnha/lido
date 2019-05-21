---
description: Event
---

# event \[Excavation\]

### Definition

#### LIDO

Identifying, descriptive and indexing information for the events in which the object participated or was present at, e.g. creation, excavation, collection, and use.

#### MNHA

This element contains the following elements:

* `eventType` \[Excavation\]
* `eventPlace` \[Excavation\]

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:event>
    <lido:eventType>
        <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">
            http://terminology.lido-schema.org/eventType/excavation
        </lido:conceptID>
        <lido:term>Fouille</lido:term>
        <lido:term xml:lang="de">Ausgrabung</lido:term>
        <lido:term xml:lang="en">Excavation</lido:term>
    <lido:eventPlace>
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
                    <lido:appellationValue>#Objets | Réf. géo. [type=lieu de trouvaille ; level 2] (fr)#</lido:appellationValue>
                    <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu de trouvaille ; level 2] (de)#</lido:appellationValue>
                    <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu de trouvaille ; level 2] (en)#</lido:appellationValue>
                </lido:namePlaceSet>
            </lido:partOfPlace>
            <lido:partOfPlace lido:politicalEntity="place">
                <lido:namePlaceSet>
                    <lido:apppellationValue>#Objets | Réf. géo. [type=lieu de trouvaille ; level 3] (fr)#</lido:appellationValue>
                    <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu de trouvaille ; level 3] (de)#</lido:appellationValue>
                    <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu de trouvaille ; level 3] (en)#</lido:appellationValue>
                </lido:namePlaceSet>
            </lido:partOfPlace>
        </lido:place>
    </lido:eventPlace>
</lido:event>
```

