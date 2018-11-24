---
description: Event Set
---

# 4.3.1 \| eventSet \[Beginning of existence\]

### Description

#### LIDO

Wrapper for the display and index elements for events \(e.g. creation, find, and use\), in which the object participated.

For multiple events repeat the element.

#### MNHA

This element contains the following element:

* `event` \[Beginning of existence\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:eventSet>
    <lido:event>
        <lido:eventType>
            <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">
                http://terminology.lido-schema.org/eventType/beginning_of_existence
            </lido:conceptID>
            <lido:term>Début d'existence</lido:term>
            <lido:term xml:lang="de">Daseinsbeginn</lido:term>
            <lido:term xml:lang="en">Beginning of existence</lido:term>
        </lido:eventType>
        <lido:eventActor>
            <lido:displayActorInRole>#Objets | Aut./Interv. 1 (fr)#</lido:displayActorInRole>
            <lido:displayActorInRole xml:lang="de">#Objets | Aut./Interv. 1 (de)#</lido:displayActorInRole>
            <lido:displayActorInRole xml:lang="en">#Objets | Aut./Interv. 1 (en)#</lido:displayActorInRole>
        </lido:eventActor>
        <lido:eventActor>
            <lido:displayActorInRole>#Objets | Aut./Interv. 2 (fr)#</lido:displayActorInRole>
            <lido:displayActorInRole xml:lang="de">#Objets | Aut./Interv. 2 (de)#</lido:displayActorInRole>
            <lido:displayActorInRole xml:lang="en">#Objets | Aut./Interv. 2 (en)#</lido:displayActorInRole>
        </lido:eventActor>
        <lido:eventDate>
            <lido:displayDate>#Objets | Dates/Siècle | Affichage (fr)#</lido:displayDate>
            <lido:displayDate xml:lang="de">#Objets | Dates/Siècle | Affichage (de)#</lido:displayDate>
            <lido:displayDate xml:lang="en">#Objets | Dates/Siècle | Affichage (en)#</lido:displayDate>
            <lido:date>
                <lido:earliestDate>#Objets | Dates/Siècle | XXX (start)#</lido:earliestDate>
                <lido:latestDate>#Objets | Dates/Siècle | XXX (end)#</lido:latestDate>
            </lido:date>
        </lido:eventDate>
        <lido:eventMaterialsTech>
            <lido:displayMaterialsTech>#Objets | Mat./Tech. 1 (fr)#</lido:displayMaterialsTech>
            <lido:displayMaterialsTech xml:lang="de">#Objets | Mat./Tech. 1 (de)#</lido:displayMaterialsTech>
            <lido:displayMaterialsTech xml:lang="en">#Objets | Mat./Tech. 1 (en)#</lido:displayMaterialsTech>
        </lido:eventMaterialsTech>
        <lido:eventMaterialsTech>
            <lido:displayMaterialsTech>#Objets | Mat./Tech. 2 (fr)#</lido:displayMaterialsTech>
            <lido:displayMaterialsTech xml:lang="de">#Objets | Mat./Tech. 2 (de)#</lido:displayMaterialsTech>
            <lido:displayMaterialsTech xml:lang="en">#Objets | Mat./Tech. 2 (en)#</lido:displayMaterialsTech>
        </lido:eventMaterialsTech>
    </lido:event>
</lido:eventSet>
```

\_\_

