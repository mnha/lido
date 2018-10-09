---
description: Object Classification Wrapper
---

# 4.1 \| objectClassificationWrap

### Definition

Wrapper for data classifying the object / work. Includes all classifying information about an object / work, such as: object / work type, style, genre, form, age, sex, and phase, or by how holding organization structures its collection \(e.g. fine art, decorative art, prints and drawings, natural science, numismatics, or local history\).

This element contains the following elements:

* objectWorkTypeWrap
* classificationWrap

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:objectClassificationWrap>
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
    <lido:classificationWrap>
        <lido:classification lido:type="designation">
            <lido:term>#Designation#</lido:term>
            <lido:term xml:lang="de">#Designation (de)#</lido:term>
            <lido:term xml:lang="en">#Designation (en)#</lido:term>
        </lido:classification>
        <lido:classification lido:type="iconography">
            <lido:term>#Iconography 1#</lido:term>
            <lido:term xml:lang="de">#Iconography 1 (de)#</lido:term>
            <lido:term xml:lang="en">#Iconography 1 (en)#</lido:term>
        </lido:classification>
        <lido:classification lido:type="iconography">
            <lido:term>#Iconography 2#</lido:term>
            <lido:term xml:lang="de">#Iconography 2 (de)#</lido:term>
            <lido:term xml:lang="en">#Iconography 2 (en)#</lido:term>
        </lido:classification>
        <lido:classification lido:type="period_style_movement">
            <lido:term>#Period | Style | Movement 1#</lido:term>
            <lido:term xml:lang="de">#Period | Style | Movement 1 (de)#</lido:term>
            <lido:term xml:lang="en">#Period | Style | Movement 1 (en)#</lido:term>
        </lido:classification>
        <lido:classification lido:type="period_style_movement">
            <lido:term>#Period | Style | Movement# 2</lido:term>
            <lido:term xml:lang="de">#Period | Style | Movement 2 (de)#</lido:term>
            <lido:term xml:lang="en">#Period | Style | Movement 2 (en)#</lido:term>
        </lido:classification>
    </lido:classificationWrap>
</lido:objectClassificationWrap>
```

