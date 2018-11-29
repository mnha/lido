---
description: Rights for Work Wrapper
---

# 5.1 \| rightsWorkWrap

### Definition

#### LIDO

Wrapper for rights information about the object / work described.

Rights information for the record and for resources is recorded in the respective rights elements recordRights and rightsResource.

#### MNHA

This element contains the following element:

* `rightsWorkSet`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:rightsWorkWrap>
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
</lido:rightsWorkWrap>
```



