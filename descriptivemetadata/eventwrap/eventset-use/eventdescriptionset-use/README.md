---
description: Event Description
---

# eventDescriptionSet \[Use\]

### Description

#### LIDO

Wrapper for a description of the event, including description identifer, descriptive note of the event and its sources.

If there is more than one descriptive note, repeat this element.

MNHA

This element contains the following element:

* `descriptiveNoteValue`

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:eventDescriptionSet>
    <lido:descriptiveNoteValue>#Objets | Utilisation 1 (fr)#</lido:descriptiveNoteValue>
    <lido:descriptiveNoteValue xml:lang="de">#Objets | Utilisation 1 (de)#</lido:descriptiveNoteValue>
    <lido:descriptiveNoteValue xml:lang="en">#Objets | Utilisation 1 (en)#</lido:descriptiveNoteValue>
</lido:eventDescriptionSet>
```

