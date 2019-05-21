---
description: Actor
---

# actor \[Beginning of existence\]

### Definition

LIDO

Describes and identifies an actor, i.e. a person, corporation, family or group, containing structured sub-elements for indexing and identification references.

#### MNHA

This element contains the following elements:

* `nameActorSet` \[Beginning of existence\]
* `vitalDatesActor` \[Beginning of existence\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:actor>
    <lido:nameActorSet>
        <lido:apppellationValue lido:label="firstname">#Auteurs/Intervenants | Prénom 1#</lido:appellationValue>
        <lido:apppellationValue lido:label="lastname">#Auteurs/Intervenants | Nom 1#</lido:appellationValue>
    </lido:nameActorSet>
    <lido:vitalDatesActor>
        <lido:earliestDate>#Auteurs/Intervenants | Dates/Siècle [type=date de naissance without Siècle] 1#</lido:earliestDate>
        <lido:latestDate>#Auteurs/Intervenants | Dates/Siècle [type=date de mort without Siècle] 1#</lido:latestDate>
    </lido:vitalDatesActor>
</lido:actor>
```

