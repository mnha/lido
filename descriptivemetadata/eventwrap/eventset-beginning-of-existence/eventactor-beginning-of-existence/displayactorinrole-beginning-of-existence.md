---
description: Display Actor in Role
---

# displayActorInRole \[Beginning of existence\]

### Definition

Display element for an actor coupled with its specific role, corresponding to the following actor element.

May include name, brief biographical information, and roles \(if necessary\) of the named actor, presented in a syntax suitable for display to the end-user and including any necessary indications of uncertainty, ambiguity, and nuance. If there is no known actor, make a reference to the presumed culture or nationality of the unknown actor. May be concatenated from the respective Actor element. The name should be in natural order, if possible, although inverted order is acceptable. Include nationality and life dates. For unknown actors, use e.g.: "unknown," "unknown Chinese," "Chinese," or "unknown 15th century Chinese." Repeat this element only for language variants.

This element contains the name and additional information of once actor.

### MuseumPlus

 Aut. \| Interv.

### Attributes

#### @xml:lang

This attribute contains the following default value:

`de` \| `en`

### Example

```markup
<lido:displayActorInRole>#Artist | Manufacturer 1 (fr)#</lido:displayActorInRole>
<lido:displayActorInRole xml:lang="de">#Artist | Manufacturer 1 (de)#</lido:displayActorInRole>
<lido:displayActorInRole xml:lang="en">#Artist | Manufacturer 1 (en)#</lido:displayActorInRole>
```

