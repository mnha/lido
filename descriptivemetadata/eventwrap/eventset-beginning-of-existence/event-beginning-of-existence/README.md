---
description: Event
---

# event \[Beginning of existence\]

### Definition

Identifying, descriptive and indexing information for the events in which the object participated or was present at, e.g. creation, excavation, collection, and use.

All information related to the creation of an object: creator, cutlural context, creation date, creation place, the material and techniques used are recorded here, qualified by the event type "creation".

This element contains the following elements:

* eventType \[Beginning of existence\]
* eventActor \[Beginning of existence\]
* eventDate \[Beginning of existence\]
* eventMaterialsTech \[Beginning of existence\]

If an event element of the type "Beginning of existence" is used, one of the subelements, eventActor, eventDate or eventMaterialsTech is mandatory.

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:event>
    <lido:eventType>
        <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">http://terminology.lido-schema.org/eventType/beginning_of_existence</lido:conceptID>
        <lido:term xml:lang="de">Daseinsbeginn</lido:term>
        <lido:term xml:lang="en">Beginning of existence</lido:term>
    </lido:eventType>
    <lido:eventActor>
        <lido:displayActorInRole>#Artist | Manufacturer 1 (fr)#</lido:displayActorInRole>
        <lido:displayActorInRole xml:lang="de">#Artist | Manufacturer 1 (de)#</lido:displayActorInRole>
        <lido:displayActorInRole xml:lang="en">#Artist | Manufacturer 1 (en)#</lido:displayActorInRole>>
    </lido:eventActor>
    <lido:eventActor>
        <lido:displayActorInRole>#Artist | Manufacturer 2 (fr)#</lido:displayActorInRole>
        <lido:displayActorInRole xml:lang="de">#Artist | Manufacturer 2 (de)#</lido:displayActorInRole>
        <lido:displayActorInRole xml:lang="en">#Artist | Manufacturer 2 (en)#</lido:displayActorInRole>
    </lido:eventActor>
    <lido:eventDate>
        <lido:displayDate>#Date(s): Display (fr)#</lido:displayDate>
        <lido:displayDate xml:lang="de">#Date(s): Display (de)#</lido:displayDate>
        <lido:displayDate xml:lang="en">#Date(s): Display (en)#</lido:displayDate>
        <lido:date>
            <lido:earliestDate>#Date (start)#</lido:earliestDate>
            <lido:latestDate>#Date (end)#</lido:latestDate>
        </lido:date>
    </lido:eventDate>
    <lido:eventMaterialsTech>
        <lido:displayMaterialsTech>#Technique | Material 1 (fr)#</lido:displayMaterialsTech>
        <lido:displayMaterialsTech xml:lang="de">#Technique | Material 1 (de)#</lido:displayMaterialsTech>
        <lido:displayMaterialsTech xml:lang="en">#Technique | Material 1 (en)#</lido:displayMaterialsTech>
    </lido:eventMaterialsTech>
    <lido:eventMaterialsTech>
        <lido:displayMaterialsTech>#Technique | Material 2 (fr)#</lido:displayMaterialsTech>
        <lido:displayMaterialsTech xml:lang="de">#Technique | Material 2 (de)#</lido:displayMaterialsTech>
        <lido:displayMaterialsTech xml:lang="en">#Technique | Material 2 (en)#</lido:displayMaterialsTech>
    </lido:eventMaterialsTech>
</lido:event>
```

