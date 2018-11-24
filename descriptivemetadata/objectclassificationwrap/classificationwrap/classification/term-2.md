---
description: Term / Label
---

# term

### Definition

A name for the referred concept, used for indexing.

This element is repeated for each language variant \(FR \| DE \| EN\).

The content of this element depends on the type attribute of the parent element classification.

### MuseumPlus

* Objets \| Collection
* Objets \| Dénomination
* Objets \| Iconographie
* Objets \| Époque / Mouv.

### Attributes

#### @xml:lang

This attribute contains the following default value:

`de` \| `en`

### Example

```markup
<lido:term>#Objets | Époque / Mouv. 1 (fr)#</lido:term>
<lido:term xml:lang="de">#Objets | Époque / Mouv. 1 (de)#</lido:term>
<lido:term xml:lang="en">#Objets | Époque / Mouv. 1 (en)#</lido:term>
```

