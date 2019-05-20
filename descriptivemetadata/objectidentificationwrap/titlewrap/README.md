---
description: Title or Object Name Wrapper
---

# 4.2.1 \| titleWrap

### Definition

#### LIDO

Wrapper for Object name / Title information.

#### MNHA

This element contains the following element:

* `titleSet`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:titleWrap>
    <lido:titleSet>
        <lido:appellationValue>#Title 1 (fr)#</lido:appellationValue>
        <lido:appellationValue xml:lang="de">#Title 1 (de)#</lido:appellationValue>
        <lido:appellationValue xml:lang="en">#Title 1 (en)#</lido:appellationValue>
    </lido:titleSet>
    <lido:titleSet>
        <lido:appellationValue>#Title 2 (fr)#</lido:appellationValue>
        <lido:appellationValue xml:lang="de">#Title 2 (de)#</lido:appellationValue>
        <lido:appellationValue xml:lang="en">#Title 2 (en)#</lido:appellationValue>
    </lido:titleSet>
    <lido:titleSet lido:type="other">
        <lido:appellationValue>#Title (other) 1 (fr)#</lido:appellationValue>
        <lido:appellationValue xml:lang="de">#Title (other) 1 (de)#</lido:appellationValue>
        <lido:appellationValue xml:lang="en">#Title (other) 1 (en)#</lido:appellationValue>
    </lido:titleSet>
    <lido:titleSet lido:type="other">
        <lido:appellationValue>#Title (other) 2 (fr)#</lido:appellationValue>
        <lido:appellationValue xml:lang="de">#Title (other) 2 (de)#</lido:appellationValue>
        <lido:appellationValue xml:lang="en">#Title (other) 2 (en)#</lido:appellationValue>
    </lido:titleSet>
</lido:titleWrap>
```

