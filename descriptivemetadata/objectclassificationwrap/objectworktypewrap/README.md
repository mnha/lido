---
description: Object/Work Type Wrapper
---

# 4.1.1 \| objectWorkTypeWrap

### Definition

A wrapper for Object/Work Types.

This element contains the following element:

* objectWorkType

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:objectWorkTypeWrap>
    <lido:objectWorkType>
        <lido:term>#Domain 1 (fr)#</lido:term>
        <lido:term xml:lang="de">#Domain 1 (de)#</lido:term>
        <lido:term xml:lang="en">#Domain 1 (en)#</lido:term>
    </lido:objectWorkType>
    <lido:objectWorkType>
        <lido:term>#Domain (fr)#</lido:term>
        <lido:term xml:lang="de">#Domain 2 (de)#</lido:term>
        <lido:term xml:lang="en">#Domain 2 (en)#</lido:term>
    </lido:objectWorkType>
</lido:objectWorkTypeWrap>
```

