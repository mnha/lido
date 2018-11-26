---
description: Inscriptions and other Marks Wrapper
---

# 4.2.2 \| inscriptionsWrap

### Definition

#### LIDO

A wrapper for information about inscriptions and other marks.

#### MNHA

This element contains the following element:

* `inscriptions`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:inscriptionsWrap>
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
    <lido:inscriptions>
        <lido:inscriptionTranscription>
            #Objets | Inscription(s) | Transcription 2#
        </lido:inscriptionTranscription>
        <lido:inscriptionDescription lido:type="type">
            <lido:descriptiveNoteValue>#Objets | Inscription(s) | Type 2 (fr)#</lido:descriptiveNoteValue>
            <lido:descriptiveNoteValue xml:lang="de">#Objets | Inscription(s) | Type 2 (de)#</lido:descriptiveNoteValue>
            <lido:descriptiveNoteValue xml:lang="en">#Objets | Inscription(s) | Type 2 (en)#</lido:descriptiveNoteValue>
        </lido:inscriptionDescription>
        <lido:inscriptionDescription lido:type="location">
            <lido:descriptiveNoteValue>#Objets | Inscription(s) | Emplacement 2 (fr)#</lido:descriptiveNoteValue>
            <lido:descriptiveNoteValue xml:lang="de">#Objets | Inscription(s) | Emplacement 2 (de)#</lido:descriptiveNoteValue>
            <lido:descriptiveNoteValue xml:lang="en">#Objets | Inscription(s) | Emplacement 2 (en)#</lido:descriptiveNoteValue>
        </lido:inscriptionDescription>
    </lido:inscriptions>
</lido:inscriptionsWrap>
```

