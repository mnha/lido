---
description: Record Wrapper
---

# 5.2 \| recordWrap

### Description

#### LIDO

A wrapper for information about the record that contains the cataloguing information.

Note that this section does not refer to any object or resource information, but only to the source record.

#### MNHA

This element contains the following elements:

* `recordID`
* `recordType`
* `recordSource`
* `recordRights` \[License\]
* `recordInfoSet` \[MuseumPlus record\]
* `recordInfoSet` \[LIDO record\]

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:recordWrap>
    <lido:recordID
        lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier"
        lido:source="MuseumPlus MNHA">
        #ID#
    </lido:recordID>
    <lido:recordType>
        <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">
            http://terminology.lido-schema.org/recordType/item-level_record
        </lido:conceptID>
        <lido:term>Item-level record</lido:term>
    </lido:recordType>
    <lido:recordSource>
        <lido:legalBodyName>
            <lido:appellationValue>Musée national d'histoire et d'art Luxembourg</lido:appellationValue>
            <lido:appellationValue xml:lang="de">Nationalmuseum für Geschichte und Kunst Luxemburg</lido:appellationValue>
            <lido:appellationValue xml:lang="en">National Museum of History and Art Luxembourg</lido:appellationValue>
        </lido:legalBodyName>
    </lido:recordSource>
    <lido:recordRights>
        <lido:rightsType>
            <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">
                https://creativecommons.org/publicdomain/zero/1.0/
            </lido:conceptID>
            <lido:term>CC0</lido:term>
            <lido:term xml:lang="de">CC0</lido:term>
            <lido:term xml:lang="en">CC0</lido:term>
        </lido:rightsType>
    </lido:recordRights>
    <lido:recordInfoSet lido:type="http://terminology.lido-schema.org/lido00471">
        <lido:recordMetadataDate lido:type="http://terminology.lido-schema.org/recordMetadataDate_type/created">
            #timestamp of record creation in MuseumPlus MNHA#
        </lido:recordMetadataDate>
        <lido:recordMetadataDate lido:type="http://terminology.lido-schema.org/recordMetadataDate_type/modified">
            #timestamp of last record edit in MuseumPlus MNHA#
        </lido:recordMetadataDate>
    </lido:recordInfoSet>
    <lido:recordInfoSet lido:type="http://terminology.lido-schema.org/lido00470">
        <lido:recordMetadataDate lido:type="http://terminology.lido-schema.org/recordMetadataDate_type/created">
            #timestamp of LIDO record creation#
        </lido:recordMetadataDate>
    </lido:recordInfoSet>
</lido:recordWrap>
```

