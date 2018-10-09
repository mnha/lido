---
description: Term / Label
---

# term

### Definition

A name for the referred concept, used for indexing.

This element is repeated for each language variant \(FR \| DE \| EN\).

The content of this element depends on the type attribute of the parent element classification.

### MuseumPlus

 Époque \| Mouv.

### Attributes

#### @xml:lang

This attribute contains the following default value:

`de` \| `en`

### Example

```markup
<lido:term>#Iconography 2#</lido:term>
<lido:term xml:lang="de">#Iconography 2 (de)#</lido:term>
<lido:term xml:lang="en">#Iconography 2 (en)#</lido:term>
```

