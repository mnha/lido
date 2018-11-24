---
description: Display Date
---

# displayDate \[Beginning of existence\]

### Description

#### LIDO

Display element for a date specification, corresponding to the following date element.

It is a concise description of the date, presented in a syntax suitable for display to the end-user and including any necessary indications of uncertainty, ambiguity, and nuance. Repeat this element only for language variants.

#### MNHA

If "Dates \| Siècle" is empty the content of this elements must be generated from the information of the subelement date in a human readable form.

### MuseumPlus

Dates \| Siècle

### Attributes

#### @xml:lang

This attribute contains the following default value:

`de` \| `en`

### Example

```markup
<lido:displayDate>#Objets | Dates/Siècle | Affichage (fr)#</lido:displayDate>
<lido:displayDate xml:lang="de">#Objets | Dates/Siècle | Affichage (de)#</lido:displayDate>
<lido:displayDate xml:lang="en">#Objets | Dates/Siècle | Affichage (en)#</lido:displayDate>
```



