---
description: Concept Identifier
---

# conceptID

### Definition

#### LIDO

A unique identifier for the concept

#### MNHA

For the element classification of the type "restriction", theis element contains the following default value:

* `RESTRICTED`

#### MuseumPlus

Vocabulaire \| Collection \| Nom interne

### Attributes

**@type**

This attribute contains the following default value:

`http://terminology.lido-schema.org/identifier_type/local_identifier`

### Example

```markup
<lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier">
    RESTRICTED
</lido:conceptID>
```

```markup
<lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier">
    #Vocabulaire | Nom interne#
</lido:conceptID>
```

