---
description: Record Type
---

# recordType

### Description

#### LIDO

Term establishing whether the record represents an individual item or a collection, series, or group of works.

Mandatory. Example values: item, collection, series, group, volume, fonds.

Preferably taken from a published controlled value list.

#### MNHA

This element distinguishes if the record describes one object or a group of objects.

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:recordType>
    <lido:conceptID
        lido:type="http://terminology.lido-schema.org/identifier_type/uri">
        http://terminology.lido-schema.org/recordType/item-level_record
    </lido:conceptID>
    <lido:term>
        Item-level record
    </lido:term>
</lido:recordType>
```

