---
description: Object
---

# object \[Bibliography\]

### Description

#### LIDO

Contains identifying information and links to another object.

#### MNHA

This element contains the following elements:

* `objectWebResource`
* `objectID`
* `objectNote`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:object>
    <lido:objectWebResource lido:formatResource="text/html">
        #Aleph LINK 1#
    </lido:objectWebResource>
    <lido:objectID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier" lido:source="a-z.lu">
        #Aleph ID 1#
    </lido:objectID>
    <lido:objectNote lido:type="book">#Bibliothèque | Réf. biblio. 1#</lido:objectNote>
    <lido:objectNote lido:type="page">#Bibliothèque | Page 1#</lido:objectNote>
    <lido:objectNote lido:type="illustration">#Bibliothèque | Ill. 1#</lido:objectNoteV>
    <lido:objectNote lido:type="catalogue">#Bibliothèque | N° catalogue 1#</lido:objectNote>
</lido:object>
```



