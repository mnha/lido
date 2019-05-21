---
description: Event
---

# event \[Beginning of existence\]

### Description

#### LIDO

Identifying, descriptive and indexing information for the events in which the object participated or was present at, e.g. creation, excavation, collection, and use.

All information related to the creation of an object: creator, cutlural context, creation date, creation place, the material and techniques used are recorded here, qualified by the event type "creation".

#### MNHA

This element contains the following elements:

* `eventType` \[Beginning of existence\]
* `eventActor` \[Beginning of existence\]
* `eventDate` \[Beginning of existence\]
* `eventPlace` \[Beginning of existence\]
* `eventMaterialsTech` \[Beginning of existence\]

If an event element of the type "Beginning of existence" is used, one of the subelements, eventActor, eventDate or eventMaterialsTech is mandatory.

### Attributes

_This element does not have attributes._

### Example

```markup
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
    </lido:eventActor>
    <lido:eventActor>
        <lido:displayActorInRole>#Objets | Aut./Interv. 2 (fr)#</lido:displayActorInRole>
        <lido:displayActorInRole xml:lang="de">#Objets | Aut./Interv. 2 (de)#</lido:displayActorInRole>
        <lido:displayActorInRole xml:lang="en">#Objets | Aut./Interv. 2 (en)#</lido:displayActorInRole>
        <lido:actorInRole>
            <lido:actor>
                <lido:nameActorSet>
                    <lido:appellationValue lido:label="firstname">#Auteurs/Intervenants | Prénom 2#</lido:appellationValue>
                    <lido:appellationValue lido:label="lastname">#Auteurs/Intervenants | Nom 2#</lido:appellationValue>
                </lido:nameActorSet>
                <lido:vitalDatesActor>
                    <lido:earliestDate>#Auteurs/Intervenants | Dates/Siècle [type=date de naissance without Siècle] 2#</lido:earliestDate>
                    <lido:latestDate>#Auteurs/Intervenants | Dates/Siècle [type=date de mort without Siècle] 2#</lido:latestDate>
                </lido:vitalDatesActor>
            </lido:actor>
            <lido:roleActor>
                <lido:term>#Objets | Aut./Interv. | Rôle 1 (fr)#</lido:term>
                <lido:term xml:lang="de">#Objets | Aut./Interv. | Rôle 2 (de)#</lido:term>
                <lido:term xml:lang="en">#Objets | Aut./Interv. | Rôle 2 (en)#</lido:term>
            </lido:roleActor>
        </lido:actorInRole>
    </lido:eventActor>
    <lido:eventDate>
        <lido:displayDate lido:label="date">#Objets | Dates/Siècle | Affichage [only date] (fr)#</lido:displayDate>
        <lido:displayDate xml:lang="de" lido:label="date">#Objets | Dates/Siècle | Affichage [only date] (de)#</lido:displayDate>
        <lido:displayDate xml:lang="en" lido:label="date">#Objets | Dates/Siècle | Affichage [only date] (en)#</lido:displayDate>
        <lido:displayDate lido:label="century">#Objets | Dates/Siècle | Affichage [only century] (fr)#</lido:displayDate>
        <lido:displayDate xml:lang="de" lido:label="century">#Objets | Dates/Siècle | Affichage [only century] (de)#</lido:displayDate>
        <lido:displayDate xml:lang="en" lido:label="century">#Objets | Dates/Siècle | Affichage [only century] (en)#</lido:displayDate>
        <lido:date>
            <lido:earliestDate>#Objets | Dates/Siècle | XXX (start)#</lido:earliestDate>
            <lido:latestDate>#Objets | Dates/Siècle | XXX (end)#</lido:latestDate>
        </lido:date>
    </lido:eventDate>
    <lido:eventPlace>
            <lido:place>
                <lido:partOfPlace lido:politicalEntity="country">
                    <lido:namePlaceSet>
                        <lido:appellationValue>#Objets | Réf. géo. [type=lieu de création ; level 1] (fr)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu de création ; level 1] (de)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu de création ; level 1] (en)#</lido:appellationValue>
                    </lido:namePlaceSet>
                </lido:partOfPlace>
                <lido:partOfPlace lido:politicalEntity="city">
                    <lido:namePlaceSet>
                        <lido:appellationValue>#Objets | Réf. géo. [type=lieu de création ; level 2] (fr)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu de création ; level 2] (de)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu de création ; level 2] (en)#</lido:appellationValue>
                    </lido:namePlaceSet>
                </lido:partOfPlace>
                <lido:partOfPlace lido:politicalEntity="place">
                    <lido:namePlaceSet>
                        <lido:appellationValue>#Objets | Réf. géo. [type=lieu de création ; level 3] (fr)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu de création ; level 3] (de)#</lido:appellationValue>
                        <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu de création ; level 3] (en)#</lido:appellationValue>
                    </lido:namePlaceSet>
                </lido:partOfPlace>
            </lido:place>
        </lido:eventPlace>
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
```

