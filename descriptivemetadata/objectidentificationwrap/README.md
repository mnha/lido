---
description: Object Identification Wrapper
---

# 4.2 \| objectIdentificationWrap

### Definition

A Wrapper for information that identifies the object.

This element contains the following elements:

* `titleWrap`
* `repositoryWrap`
* `objectDescriptionWrap`
* `objectMeasurementsWrap`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:objectIdentificationWrap>
    <lido:titleWrap>
        <lido:titleSet>
            <lido:appellationValue>#Title (fr)#</lido:appellationValue>
            <lido:appellationValue xml:lang="de">#Title (de)#</lido:appellationValue>
            <lido:appellationValue xml:lang="en">#Title (en)#</lido:appellationValue>
        </lido:titleSet>
        <lido:titleSet lido:type="other">
            <lido:appellationValue>#Title (other) 1 (fr)#</lido:appellationValue>
            <lido:appellationValue xml:lang="de">#Title (other) 1 (de)#</lido:appellationValue>
            <lido:appellationValue xml:lang="en">#Title (other) 1 (en)#</lido:appellationValue>
        </lido:titleSet>
        <lido:titleSet lido:type="other">
            <lido:appellationValue>#Title (other) 2 (fr)#</lido:appellationValue>
            <lido:appellationValue xml:lang="de">#Title (other) 2 (de)#</lido:appellationValue>
            <lido:appellationValue xml:lang="en">#Title (other) 2 (en)#</lido:appellationValue>
        </lido:titleSet>
    </lido:titleWrap>
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
    <lido:repositoryWrap>
        <lido:repositorySet
            lido:type="http://terminology.lido-schema.org/repositorySet_type/current_repository_or_location">
            <lido:repositoryName>
                <lido:legalBodyName>
                    <lido:appellationValue>Musée national d'histoire et d'art Luxembourg</lido:appellationValue>
                    <lido:appellationValue xml:lang="de">Nationalmuseum für Geschichte und Kunst Luxemburg</lido:appellationValue>
                    <lido:appellationValue xml:lang="en">National Museum of History and Art Luxembourg</lido:appellationValue>
                </lido:legalBodyName>
                <lido:legalBodyWeblink>http://www.mnha.lu</lido:legalBodyWeblink>
            </lido:repositoryName>
            <lido:workID>
                #Inventory Number#
            </lido:workID>
            <lido:repositoryLocation>
                <lido:placeID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier">
                    #Location in museum (Link)#
                </lido:placeID>
                <lido:namePlaceSet>
                    <lido:appellationValue>#Objets | Empl. actuel (Text) (fr)#</lido:appellationValue>
                    <lido:appellationValue xml:lang="de">#Objets | Empl. actuel (Text) (de)#</lido:appellationValue>
                    <lido:appellationValue xml:lang="en">#Objets | Empl. actuel (Text) (en)#</lido:appellationValue>
                </lido:namePlaceSet>
            </lido:repositoryLocation>
        </lido:repositorySet>
    </lido:repositoryWrap>
    <lido:objectDescriptionWrap>
        <lido:objectDescriptionSet>
            <lido:descriptiveNoteValue>#Objets | Description (fr)#</lido:descriptiveNoteValue>
            <lido:descriptiveNoteValue xml:lang="de">#Objets | Description (de)#</lido:descriptiveNoteValue>
            <lido:descriptiveNoteValue xml:lang="en">#Objets | Description (en)#</lido:descriptiveNoteValue>
        </lido:objectDescriptionSet>
    </lido:objectDescriptionWrap>
    <lido:objectMeasurementsWrap>
        <lido:objectMeasurementsSet>
            <lido:displayObjectMeasurements>#Objets | Dimensions 1 (fr)#</lido:displayObjectMeasurements>
            <lido:displayObjectMeasurements xml:lang="de">#Objets | Dimensions 1 (de)#</lido:displayObjectMeasurements>
            <lido:displayObjectMeasurements xml:lang="en">#Objets | Dimensions 1 (en)#</lido:displayObjectMeasurements>
        </lido:objectMeasurementsSet>
        <lido:objectMeasurementsSet>
            <lido:displayObjectMeasurements>#Objets | Dimensions 2 (fr)#</lido:displayObjectMeasurements>
            <lido:displayObjectMeasurements xml:lang="de">#Objets | Dimensions 2 (de)#</lido:displayObjectMeasurements>
            <lido:displayObjectMeasurements xml:lang="en">#Objets | Dimensions 2 (en)#</lido:displayObjectMeasurements>
        </lido:objectMeasurementsSet>
    </lido:objectMeasurementsWrap>
</lido:objectIdentificationWrap>
```



