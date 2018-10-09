---
description: Classification
---

# classification

### Definition

Concepts used to categorize an object / work by grouping it together with others on the basis of similar characteristics.

The category belongs to a systematic scheme \(classification\) which groups objects of similar characteristics according to uniform aspects. This grouping / classification may be done according to material, form, shape, function, region of origin, cultural context, or historical or stylistic period. In addition to this systematic grouping it may also be done according to organizational divisions within a museum \(e.g., according to the collection structure of a museum\). If the object / work is assigned to multiple classifications, repeat this element. Preferably taken from a published controlled vocabulary.

### Attributes

#### @type

This attribute contains the following values to specify the content of the subelement term:

`designation`

The content of the subelement termis from the MuseumPlus field "Dénomination"

`iconography`

The content of the subelement termis from the MuseumPlus field "Iconographie"

`period_style_movement`

The content of the subelement termis from the MuseumPlus field "Époque \| Mouv."

### Example

```markup
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
```

