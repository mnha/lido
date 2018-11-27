---
description: Description/Descriptive Note Set
---

# objectDescriptionSet

### Definition

#### LIDO

Wrapper for a description of the object, including description identifer, descriptive note and sources.

Includes usually a relatively brief essay-like text that describes the content and context of the object / work, including comments and an interpretation that may supplement, qualify, or explain the physical characteristics, subject, circumstances of creation or discovery, or other information about it. If there is more than one descriptive note, repeat this element.

A reference to a text resource holding the description may be given in description identifier.

#### MNHA

This element contains teh following element:

* `descriptiveNoteValue`

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:objectDescriptionSet>
    <lido:descriptiveNoteValue>#Objets | Description (fr)#</lido:descriptiveNoteValue>
    <lido:descriptiveNoteValue xml:lang="de">#Objets | Description (de)#</lido:descriptiveNoteValue>
    <lido:descriptiveNoteValue xml:lang="en">#Objets | Description (en)#</lido:descriptiveNoteValue>
</lido:objectDescriptionSet>
```



