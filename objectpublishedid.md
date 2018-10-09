---
description: Published Object Identifier
---

# 2 \| objectPublishedID

### Definition

A unique, published identification of the described object / work.

May link to authority files maintained outside of the contributor's documentation system or may be an identifier for the object published by its repository, e.g. composed of an identifier for the repository and an inventory number of the object. Preferably a dereferenceable URL.

This element contains the link to the described object in the MNHA Portal. It consists of a static prefix and the Unique Identifier.

### MuseumPlus

xxx

### Attributes

#### @type

This attribute contains the following default value:

`http://terminology.lido-schema.org/identifier_type/uri`

### Example

```markup
<lido:objectPublishedID 
lido:type="http://terminology.lido-schema.org/identifier_type/uri">
#portal prefix# + #Unique Identifier#
</lido:objectPublishedID>
```

