---
description: Rights Type
---

# rightsType

### Description

#### LIDO

The specific type of right being recorded.

#### MNHA

This element contains the following elements:

* `conceptID`
* `term`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:rightsType>
    <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">
        #URI#
    </lido:conceptID>
    <lido:term>#URI display text (fr)#</lido:term>
    <lido:term xml:lang="de">#URI display text (de)#</lido:term>
    <lido:term xml:lang="en">#URI display text (en)#</lido:term>
</lido:rightsType>
```

