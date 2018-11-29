---
description: Record Metadata Date
---

# recordMetadataDate \[MuseumPlus record\]

### Description

#### LIDO

Creation date or date modified of the metadata record. Format will vary depending upon implementation.

#### MNHA

This element is generated twice using each type attribute value. If a source record was not modified after creation the modified timestamp is the same as the created timestamp.

The timestamp is encoded in ISO 8601.

### MuseumPlus

xxx

### Attributes

#### @type

This attribute contains one of the following values:

* `http://terminology.lido-schema.org/recordMetadataDate_type/created`
* `http://terminology.lido-schema.org/recordMetadataDate_type/modified`

### Example

```markup
<lido:recordMetadataDate lido:type="http://terminology.lido-schema.org/recordMetadataDate_type/created">
    #timestamp of record creation in MuseumPlus MNHA#
</lido:recordMetadataDate>
<lido:recordMetadataDate lido:type="http://terminology.lido-schema.org/recordMetadataDate_type/modified">
    #timestamp of last record edit in MuseumPlus MNHA#
</lido:recordMetadataDate>
```

