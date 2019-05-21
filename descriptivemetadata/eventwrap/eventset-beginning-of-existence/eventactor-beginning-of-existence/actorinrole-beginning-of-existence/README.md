---
description: Actor in Role
---

# actorInRole \[Beginning of existence\]

### Definition

#### LIDO

Describes an actor with role and \(if necessary\) attributions in a structured way, consisting of the sub-elements actor, its role, attribution and extent.

#### MNHA

This element contains the following elements:

* `actor` \[Beginning of existence\]
* `roleActor` \[Beginning of existence\]

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:actorInRole>
    <lido:actor>
        <lido:nameActorSet>
            <lido:appellationValue lido:label="firstname">#Auteurs/Intervenants | Prénom 1#</lido:appellationValue>
            <lido:appellationValue lido:label="lastname">#Auteurs/Intervenants | Nom 1#</lido:appellationValue>
        </lido:nameActorSet>
        <lido:vitalDatesActor>
            <lido:earliestDate>#Auteurs/Intervenants | Dates/Siècle [type=date de naissance without Siècle] 1#</lido:earliestDate>
            <lido:latestDate>#Auteurs/Intervenants | Dates/Siècle [type=date de mort without Siècle] 1#</lido:latestDate>
        </lido:vitalDatesActor>
    </lido:actor>
    <lido:roleActor>
        <lido:term>#Objets | Aut./Interv. | Rôle 1 (fr)#</lido:term>
        <lido:term xml:lang="de">#Objets | Aut./Interv. | Rôle 1 (de)#</lido:term>
        <lido:term xml:lang="en">#Objets | Aut./Interv. | Rôle 1 (en)#</lido:term>
    </lido:roleActor>
</lido:actorInRole>
```

