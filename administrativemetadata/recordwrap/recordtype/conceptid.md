---
description: Concept Identifier
---

# conceptID

### Description

#### LIDO

A unique identifier for the concept.

Preferably taken from and linking to a published controlled vocabulary.

#### MNHA

This element contains the following value:

* `http://terminology.lido-schema.org/recordType/item-level_record`

### Attributes

#### @type

This attribute contains the following default value:

* `http://terminology.lido-schema.org/identifier_type/uri`

### Example

```markup
<lido:conceptID
    lido:type="http://terminology.lido-schema.org/identifier_type/uri">
    http://terminology.lido-schema.org/recordType/item-level_record
</lido:conceptID>
```

