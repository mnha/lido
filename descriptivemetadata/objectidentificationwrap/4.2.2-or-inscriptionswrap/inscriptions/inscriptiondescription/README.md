---
description: Inscription Description
---

# inscriptionDescription

### Definition

#### LIDO

Wrapper for a description of the inscription, including description identifier, descriptive note of the inscription and sources.

#### MNHA

This element contains the following element:

* `descriptiveNoteValue`

### Attributes

**@type**

This attribute contains the following default values:

`type | location`

### Example

```markup
<lido:inscriptionDescription lido:type="type">
    <lido:descriptiveNoteValue>#Objets | Inscription(s) | Type 1 (fr)#</lido:descriptiveNoteValue>
    <lido:descriptiveNoteValue xml:lang="de">#Objets | Inscription(s) | Type 1 (de)#</lido:descriptiveNoteValue>
    <lido:descriptiveNoteValue xml:lang="en">#Objets | Inscription(s) | Type 1 (en)#</lido:descriptiveNoteValue>
</lido:inscriptionDescription>
<lido:inscriptionDescription lido:type="location">
    <lido:descriptiveNoteValue>#Objets | Inscription(s) | Emplacement 1 (fr)#</lido:descriptiveNoteValue>
    <lido:descriptiveNoteValue xml:lang="de">#Objets | Inscription(s) | Emplacement 1 (de)#</lido:descriptiveNoteValue>
    <lido:descriptiveNoteValue xml:lang="en">#Objets | Inscription(s) | Emplacement 1 (en)#</lido:descriptiveNoteValue>
</lido:inscriptionDescription>
```

