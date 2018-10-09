---
description: Custody/Repository Location Set
---

# repositorySet

### Definition

Wrapper for designation and identification of the institution of custody, and possibly an indication of the exact location of the object.

This element contains the following elements:

* repositoryName
* workID
* repositoryLocation

### Attributes

#### @type

This attribute contains the following default value:

`http://terminology.lido-schema.org/repositorySet_type/current_repository_or_location`

### Example

```markup
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
```

