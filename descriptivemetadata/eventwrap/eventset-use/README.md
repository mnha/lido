---
description: Event Set
---

# 4.3.2 \| eventSet \[Use\]

### Description

#### LIDO

Wrapper for the display and index elements for events \(e.g. creation, find, and use\), in which the object participated.

For multiple events repeat the element.

#### MNHA

This element contains the following element:

* event \[Use\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:eventSet>
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
</lido:eventSet>
<lido:eventSet>
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
            <lido:descriptiveNoteValue>#Objets | Utilisation 2 (fr)#</lido:descriptiveNoteValue>
            <lido:descriptiveNoteValue xml:lang="de">#Objets | Utilisation 2 (de)#</lido:descriptiveNoteValue>
            <lido:descriptiveNoteValue xml:lang="en">#Objets | Utilisation 2 (en)#</lido:descriptiveNoteValue>
        </lido:eventDescriptionSet>
    </lido:event>
</lido:eventSet>
```

