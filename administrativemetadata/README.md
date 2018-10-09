---
description: Administrative Metadata
---

# 5 \| administrativeMetadata

### Definition

Holds the administrative metadata for an object / work record.

The attribute xml:lang is mandatory and specifies the language of the administrative metadata.

For fully multi-lingual resources, repeat this element once for each language represented.

If only a few data fields \(e.g. title, creditline\) are provided in more than one language, the respective text elements may be repeated specifying the lang attribute on the text level.

This element contains the following elements:

* rightsWorkWrap
* recordWrap
* recordWrap

### Attributes

#### @xml:lang

This attribute contains the following default value:

`fr`

### Example

```markup
<lido:administrativeMetadata xml:lang="fr">
    <lido:rightsWorkWrap>
        ...
    </lido:rightsWorkWrap>
    <lido:recordWrap>
        ...
    </lido:recordWrap>
    <lido:resourceWrap>
        ...
    </lido:resourceWrap>
</lido:administrativeMetadata>
```

