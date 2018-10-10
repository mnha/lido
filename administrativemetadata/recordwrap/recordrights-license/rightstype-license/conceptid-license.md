---
description: Concept Identifier
---

# conceptID \[License\]

### Description

#### LIDO

A unique identifier for the concept.

Preferably taken from and linking to a published controlled vocabulary.

#### MNHA

This element is only optional if a non-standard license without a URI is used otherwise it is mandatory.

### MuseumPlus

{% hint style="info" %}
The field does not exist yet!
{% endhint %}

### Attributes

#### @type

This attribute contains the following default value:

* `http://terminology.lido-schema.org/identifier_type/uri`

### Example

```markup
<lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">
    #The field does not exist yet#
</lido:conceptID>
```

