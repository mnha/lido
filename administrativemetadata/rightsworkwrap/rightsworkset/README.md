---
description: Rights for Work Set
---

# 5.1.1 \| rightsWorkSet

### Description

#### LIDO

Information about rights management; may include copyright and other intellectual property statements about the object / work.

#### MNHA

This element contains the following elements:

* `rightsType`
* `creditLine`

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:rightsWorkSet>
    <lido:rightsType>
        <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">
            #URI#
        </lido:conceptID>
        <lido:term>#URI display text (fr)#</lido:term>
        <lido:term xml:lang="de">#URI display text (de)#</lido:term>
        <lido:term xml:lang="en">#URI display text (en)#</lido:term>
    </lido:rightsType>
    <lido:creditLine>#Objets | Mention droits (fr)#</lido:creditLine>
    <lido:creditLine xml:lang="de">#Objets | Mention droits (de)#</lido:creditLine>
    <lido:creditLine xml:lang="en">#Objets | Mention droits (en)#</lido:creditLine>
</lido:rightsWorkSet>
```

