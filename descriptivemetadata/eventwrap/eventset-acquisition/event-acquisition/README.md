---
description: Event
---

# event \[Acquisition\]

### Description

#### LIDO

Identifying, descriptive and indexing information for the events in which the object participated or was present at, e.g. creation, excavation, collection, and use.

All information related to the creation of an object: creator, cutlural context, creation date, creation place, the material and techniques used are recorded here, qualified by the event type "creation".

#### MNHA

This element contains the following elements:

* `eventType` \[Acquisition\]
* `eventDate` \[Acquisition\]
* `eventMethod` \[Acquisition\]
* `eventDescriptionSet` \[Acquisition\]

If an event element of the type “Acquisition” is used, one of the subelements eventActor, eventMethod or eventDescriptionSet is mandatory.

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:event>
    <lido:eventType>
        <lido:conceptID
            lido:type="http://terminology.lido-schema.org/identifier_type/uri">http://terminology.lido-schema.org/eventType/acquisition
        </lido:conceptID>
        <lido:term>Acquisition</lido:term>
        <lido:term xml:lang="de">Erwerbung</lido:term>
        <lido:term xml:lang="en">Acquisition</lido:term>
    </lido:eventType>
    <lido:eventDate>
        <lido:displayDate>#Objets | Date d'acq.#</lido:displayDate>
        <lido:date>
            <lido:earliestDate>#Acquisition date ISO 8601#</lido:earliestDate>
            <lido:latestDate>#Acquisition date ISO 8601#</lido:latestDate>
        </lido:date>
    </lido:eventDate>
    <lido:eventMethod>
        <lido:term>#Objets | Mode d'acq. (fr)#</lido:term>
        <lido:term xml:lang="de">#Objets | Mode d'acq. (de)#</lido:term>
        <lido:term xml:lang="de">#Objets | Mode d'acq. (en)#</lido:term>
    </lido:eventMethod>
    <lido:eventDescriptionSet>
        <lido:descriptiveNoteValue>#Objets | Mention obl. (fr)#</lido:descriptiveNoteValue>
        <lido:descriptiveNoteValue xml:lang="de">#Objets | Mention obl. (de)#</lido:descriptiveNoteValue>
        <lido:descriptiveNoteValue xml:lang="en">#Objets | Mention obl. (en)#</lido:descriptiveNoteValue>
    </lido:eventDescriptionSet>
</lido:event>
```

