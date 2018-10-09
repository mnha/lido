---
description: Object Identification Wrapper
---

# 4.2 \| objectIdentificationWrap

### Definition

A Wrapper for information that identifies the object.

This element contains the following elements:

* titleWrap
* repositoryWrap
* objectDescriptionWrap
* objectMeasurementsWrap

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:objectIdentificationWrap>
    <lido:titleWrap>
        <lido:titleSet>
            <lido:appellationValue>#Title (fr)#</lido:appellationValue>
            <lido:appellationValue xml:lang="en">#Title (en)#</lido:appellationValue>
            <lido:appellationValue xml:lang="de">#Title (de)#</lido:appellationValue>
        </lido:titleSet>
    </lido:titleWrap>
    <lido:repositoryWrap>
        <lido:repositorySet lido:type="http://terminology.lido-schema.org/repositorySet_type/current_repository_or_location">
            <lido:repositoryName>
                <lido:legalBodyName>
                    <lido:appellationValue>Musée national d'histoire et d'art Luxembourg</lido:appellationValue>
                    <lido:appellationValue xml:lang="de">Nationalmuseum für Geschichte und Kunst Luxemburg</lido:appellationValue>
                    <lido:appellationValue xml:lang="en">National Museum of History and Art Luxembourg</lido:appellationValue>
                </lido:legalBodyName>
                <lido:legalBodyWeblink>http://www.mnha.lu</lido:legalBodyWeblink>
            </lido:repositoryName>
            <lido:workID>#Inventory Number#</lido:workID>
            <lido:repositoryLocation>
                <lido:placeID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier">
                    #Location in museum (Link)#
                </lido:placeID>
                <lido:namePlaceSet>
                    <lido:appellationValue>#Location in museum (Text) (fr)#</lido:appellationValue>
                    <lido:appellationValue xml:lang="de">#Location in museum (Text) (de)#</lido:appellationValue>
                    <lido:appellationValue xml:lang="en">#Location in museum (Text) (en)#</lido:appellationValue>
                </lido:namePlaceSet>
            </lido:repositoryLocation>
        </lido:repositorySet>
    </lido:repositoryWrap>
    <lido:objectDescriptionWrap>
        <lido:objectDescriptionSet>
            <lido:descriptiveNoteValue>#Description (fr)#</lido:descriptiveNoteValue>
            <lido:descriptiveNoteValue xml:lang="de">#Description (de)#</lido:descriptiveNoteValue>
            <lido:descriptiveNoteValue xml:lang="en">#Description (en)#</lido:descriptiveNoteValue>
        </lido:objectDescriptionSet>
    </lido:objectDescriptionWrap>
    <lido:objectMeasurementsWrap>
        <lido:objectMeasurementsSet>
            <lido:displayObjectMeasurements>#Dimensions 1 (fr)#</lido:displayObjectMeasurements>
            <lido:displayObjectMeasurements xml:lang="de">#Dimensions 1 (de)#</lido:displayObjectMeasurements>
            <lido:displayObjectMeasurements xml:lang="en">#Dimensions 1 (en)#</lido:displayObjectMeasurements>
        </lido:objectMeasurementsSet>
        <lido:objectMeasurementsSet>
            lido:displayObjectMeasurements>#Dimensions 2 (fr)#</lido:displayObjectMeasurements>
            <lido:displayObjectMeasurements xml:lang="de">#Dimensions 2 (de)#</lido:displayObjectMeasurements>
            <lido:displayObjectMeasurements xml:lang="en">#Dimensions 2 (en)#</lido:displayObjectMeasurements>
        </lido:objectMeasurementsSet>
    </lido:objectMeasurementsWrap>
</lido:objectIdentificationWrap>
```



