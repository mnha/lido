---
description: Event Set
---

# 4.3.3 \| eventSet \[Acquisition\]

### Description

#### LIDO

Wrapper for the display and index elements for events \(e.g. creation, find, and use\), in which the object participated.

For multiple events repeat the element.

#### MNHA

This element contains the following element:

* `event` \[Acquisition\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:eventSet>
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
</lido:eventSet>
```

