---
description: Event Actor
---

# eventActor \[Beginning of existence\]

### Description

#### LIDO

Wrapper for display and index elements for an actor with role information \(participating or being present in the event\).

This element is repeated for multiple artists / manufacturers.

#### MNHA

This element contains the following element:

* `displayActorInRole` \[Beginning of existence\]
* `actorInRole` \[Beginning of existence\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:eventActor>
    <lido:displayActorInRole>#Objets | Aut./Interv. 1 (fr)#</lido:displayActorInRole>
    <lido:displayActorInRole xml:lang="de">#Objets | Aut./Interv. 1 (de)#</lido:displayActorInRole>
    <lido:displayActorInRole xml:lang="en">#Objets | Aut./Interv. 1 (en)#</lido:displayActorInRole>
    <lido:actorInRole>
        <lido:actor>
            <lido:nameActorSet>
                <lido:appellationValue lido:label="firstname">#Auteurs/Intervenants | Prénom 1#</lido:appellationValue>
                <lido:appellationValue lido:label="lastname">#Auteurs/Intervenants | Nom 1#</lido:appellationValue>
            </lido:nameActorSet>
            <lido:vitalDatesActor>
                <lido:earliestDate>#Auteurs/Intervenants | Dates/Siècle [type=date de naissance without Siècle] 1#</lido:earliestDate>
                <lido:latestDate>#Auteurs/Intervenants | Dates/Siècle [type=date de mort without Siècle] 1#</lido:latestDate>
            <lido:vitalDatesActor>
        </lido:actor>
        <lido:roleActor>
            <lido:term>#Objets | Aut./Interv. | Rôle 1 (fr)#</lido:term>
            <lido:term xml:lang="de">#Objets | Aut./Interv. | Rôle 1 (de)#</lido:term>
            <lido:term xml:lang="en">#Objets | Aut./Interv. | Rôle 1 (en)#</lido:term>
        </lido:roleActor>
    </lido:actorInRole>
</lido:eventActor>
```

\_\_

