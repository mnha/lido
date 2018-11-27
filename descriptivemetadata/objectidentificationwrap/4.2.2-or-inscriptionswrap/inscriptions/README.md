---
description: Inscriptions
---

# inscriptions

### Definition

#### LIDO

A transcription or description of any distinguishing or identifying physical lettering, annotations, texts, markings, or labels that are affixed, applied, stamped, written, inscribed, or attached to the object / work, excluding any mark or text inherent in the materials of which it is made.

#### MNHA

This element contains the following elements:

* `inscriptionTranscription`
* `inscriptionDescription`

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:inscriptions>
    <lido:inscriptionTranscription>
        #Objets | Inscription(s) | Transcription 1#
    </lido:inscriptionTranscription>
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
</lido:inscriptions>
```

