---
description: Record Metadata Information Set
---

# recordInfoSet \[MuseumPlus record\]

### Description

#### LIDO

Wrapper for metadata information about this record.

#### MNHA

This element contains information about the source record in MuseumPlus \(MNHA\).

### Attributes

#### @type

This attribute contains the following default value:

* `http://terminology.lido-schema.org/lido00471`

{% hint style="info" %}
This yet unpublished URI from the LIDO Terminology relates the contained information to the "source record".
{% endhint %}

### Example

```markup
<lido:recordInfoSet lido:type="http://terminology.lido-schema.org/lido00471">
    <lido:recordMetadataDate lido:type="http://terminology.lido-schema.org/recordMetadataDate_type/created">#timestamp of record creation in MuseumPlus MNHA#</lido:recordMetadataDate>
    <lido:recordMetadataDate lido:type="http://terminology.lido-schema.org/recordMetadataDate_type/modified">#timestamp of last record edit in MuseumPlus MNHA#</lido:recordMetadataDate>
</lido:recordInfoSet>
```

