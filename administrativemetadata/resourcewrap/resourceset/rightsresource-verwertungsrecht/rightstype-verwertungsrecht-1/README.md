---
description: Rights Type
---

# rightsType \[License\]

### Description

#### LIDO

The specific type of right being recorded.

For example: copyright, publication right, data protection right, trademark. Preferably taken from a published controlled value list.

#### MNHA

This element contains the following default value:

* `conceptID` \[License\]
* `term` \[License\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:rightsType>
    <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">#URI#</lido:conceptID>
    <lido:term>#URI display text (fr)#</lido:term>
    <lido:term xml:lang="de">#URI display text (de)#</lido:term>
    <lido:term xml:lang="en">#URI display text (en)#</lido:term>
</lido:rightsType>
```

