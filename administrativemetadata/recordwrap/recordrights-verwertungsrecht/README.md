---
description: Rights for Record
---

# 5.2.4 \| recordRights \[License\]

### Description

#### LIDO

Information about rights regarding the content provided in this LIDO record.

#### MNHA

This element contains the following elements:

* `rightsType` \[License\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
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
```

