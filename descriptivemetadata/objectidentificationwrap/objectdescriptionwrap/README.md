---
description: Object Description/Descriptive Note Wrapper
---

# 4.2.4 \| objectDescriptionWrap

### Definition

#### LIDO

A wrapper for Description/Descriptive Note information.

#### MNHA

This element contains the following element:

* `objectDescriptionSet`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:objectDescriptionWrap>
    <lido:objectDescriptionSet lido:type="short">
        <lido:descriptiveNoteValue>#Objets | Textes [type = Descr. courte] (fr)#</lido:descriptiveNoteValue>
        <lido:descriptiveNoteValue xml:lang="de">#Textes | Description [type = Descr. courte](de)#</lido:descriptiveNoteValue>
        <lido:descriptiveNoteValue xml:lang="en">#Textes | Description [type = Descr. courte] (en)#</lido:descriptiveNoteValue>
    </lido:objectDescriptionSet>
    <lido:descriptionSet lido:type="long">
        <lido:descriptiveNoteValue>#Objets | Textes [type = Descr. longue] (fr)#</lido:descriptiveNoteValue>
        <lido:descriptiveNoteValue xml:lang="de">#Objets | Textes [type = Descr. longue] (de)#</lido:descriptiveNoteValue>
        <lido:descriptiveNoteValue xml:lang="en">#Objets | Textes [type = Descr. longue] (en)#</lido:descriptiveNoteValue>
</lido:objectDescriptionWrap>
```

