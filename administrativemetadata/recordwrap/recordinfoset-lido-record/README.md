---
description: Record Metadata Information Set
---

# recordInfoSet \[LIDO record\]

### Description

#### LIDO

Wrapper for metadata information about this record.

#### MNHA

This element contains information about the lido record generated during the export out of MuseumPlus \(MNHA\).

### Attributes

#### @type

This attribute contains the following default value:

* `http://terminology.lido-schema.org/lido00470`

{% hint style="info" %}
This yet unpublished URI from the LIDO Terminology relates the contained information to the "lido record".
{% endhint %}

Example

```markup
<lido:recordInfoSet lido:type="http://terminology.lido-schema.org/lido00470">
    <lido:recordMetadataDate lido:type="http://terminology.lido-schema.org/recordMetadataDate_type/created">
        #timestamp of LIDO record creation#
    </lido:recordMetadataDate>
</lido:recordInfoSet>
```

