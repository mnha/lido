---
description: Resource Identification Number
---

# 5.3.1.1 \| resourceID

### Description

#### LIDO

The unique numeric or alphanumeric identification of the original \(digital or analogue\) resource.

#### MNHA

This element contains the filename of the image file after the export out of MuseumPlus.

### MuseumPlus

{% hint style="info" %}
Filename of the image
{% endhint %}

### Attributes

#### @type

This attribute contains the following value:

* `http://terminology.lido-schema.org/identifier_type/local_identifier`

#### @source

This attribute contains the following value:

* `MuseumPlus MNHA`

### Example

```markup
<lido:resourceID
    lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier"
    lido:source="MuseumPlus MNHA">
    #local filename#
</lido:resourceID>
```

