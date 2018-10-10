---
description: Object/Work Type
---

# objectWorkType

### Description

#### LIDO

The specific kind of object / work being described.

Preferably taken from a published controlled vocabulary. For a collection, include repeating instances for identifying all of or the most important items in the collection.

#### MNHA

This element is repeated for each domain.

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:objectWorkType>
    <lido:term>#Domaine(s) 1 (fr)#</lido:term>
    <lido:term xml:lang="de">#Domaine(s) 1 (de)#</lido:term>
    <lido:term xml:lang="en">#Domaine(s) 1 (en)#</lido:term>
</lido:objectWorkType>
<lido:objectWorkType>
    <lido:term>#Domaine(s) (fr)#</lido:term>
    <lido:term xml:lang="de">#Domaine(s) 2 (de)#</lido:term>
    <lido:term xml:lang="en">#Domaine(s) 2 (en)#</lido:term>
</lido:objectWorkType>
```

\_\_

