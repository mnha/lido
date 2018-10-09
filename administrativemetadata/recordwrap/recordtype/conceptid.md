---
description: Concept Identifier
---

# conceptID

### Description

#### LIDO

A unique identifier for the concept.

Preferably taken from and linking to a published controlled vocabulary.

#### MNHA

This element contains one of the following values:

* `http://terminology.lido-schema.org/recordType/item-level_record`
* `http://terminology.lido-schema.org/recordType/group-level_record`

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

