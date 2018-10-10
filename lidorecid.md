---
description: LIDO Metadata Record-ID
---

# 1 \| lidoRecID

### Description

#### LIDO

A unique lido record identification preferably composed of an identifier for the contributor and a record identification in the contributor's \(local\) system.

#### MNHA

This element contains the unique identifier of the LIDO record.

{% hint style="info" %}
The Goobi Viewer only allows letters, numbers, underscores and hyphens in the identifier.
{% endhint %}

### MuseumPlus

ID

Format: mnha\[ID\]

Example: mnha38837

### Attributes

#### @type

This attribute contains the following default value:

`http://terminology.lido-schema.org/identifier_type/local_identifier`

### **Example**

```markup
<lido:lidoRecID 
lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier">
    #mnha[ID]#
</lido:lidoRecID>
```



