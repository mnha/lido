---
description: Event
---

# event \[Use\]

### Description

#### LIDO

Identifying, descriptive and indexing information for the events in which the object participated or was present at, e.g. creation, excavation, collection, and use.

All information related to the creation of an object: creator, cutlural context, creation date, creation place, the material and techniques used are recorded here, qualified by the event type "creation".

#### MNHA

This element contains the following elements:

* `eventType` \[Use\]
* `eventDescriptionSet` \[Use\]

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:event>
    <lido:eventType>
        <lido:conceptID
            lido:type="http://terminology.lido-schema.org/identifier_type/uri">http://terminology.lido-schema.org/eventType/use
        </lido:conceptID>
        <lido:term>Utilisation</lido:term>
        <lido:term xml:lang="de">Gebrauch</lido:term>
        <lido:term xml:lang="en">Use</lido:term>
    </lido:eventType>
    <lido:eventDescriptionSet>
        <lido:descriptiveNoteValue>#Objets | Utilisation 1 (fr)#</lido:descriptiveNoteValue>
        <lido:descriptiveNoteValue xml:lang="de">#Objets | Utilisation 1 (de)#</lido:descriptiveNoteValue>
        <lido:descriptiveNoteValue xml:lang="en">#Objets | Utilisation 1 (en)#</lido:descriptiveNoteValue>
    </lido:eventDescriptionSet>
</lido:event>
```

