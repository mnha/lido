---
description: Descriptive Metadata
---

# 4 \| descriptiveMetadata

### Definition

Holds the descriptive metadata of an object record.

The attribute xml:lang is mandatory and specifies the language of the descriptive metadata. For fully multi-lingual resources, repeat this element once for each language represented.

If only a few data fields \(e.g. title\) are provided in more than one language, the respective text elements may be repeated specifying the lang attribute on the text level.

{% hint style="info" %}
MNHA collections platform: for all data fields that are provided in more than one language \(FR \| DE \| EN\), the respective test elements are repeated specifying the lang attribute on the text level.
{% endhint %}

This element contains the following elements:

* objectClassificationWrap
* objectIdentificationWrap
* eventWrap
* obkectRelationWrap

### Attributes

#### @xml:lang

This attribute contains the following default value:

`fr`

### Example

```markup
<lido:descriptiveMetadata xml:lang="fr">
    <lido:objectClassificationWrap>
        ...
    </lido:objectClassificationWrap>
    <lido:objectIdentificationWrap>
        ...
    </lido:objectIdentificationWrap>
    <lido:eventWrap>
        ...
    </lido:eventWrap>
    <lido:objectRelationWrap>
        ...
    </lido:objectRelationWrap>
</lido:descriptiveMetadata>
```

