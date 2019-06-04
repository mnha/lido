---
description: Related Work
---

# relatedWork \[Bibliography\]

### Description

#### LIDO

Wrapper for the display and reference elements of a related object/work.

#### MNHA

This element contains the following elements

* `object`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:relatedWork>               
    <lido:object>
        <lido:objectWebResource lido:formatResource="text/html">
            #Aleph LINK#
        </lido:objectWebResource>
        <lido:objectID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier" lido:source="a-z.lu">
            #Aleph ID#
        </lido:objectID>
        <lido:objectNote lido:type="book">#Bibliothèque | Réf. biblio. 1#</lido:objectNote>
        <lido:objectNote lido:type="page">#Bibliothèque | Page 1#</lido:objectNote>
        <lido:objectNote lido:type="illustration">#Bibliothèque | Ill. 1#</lido:objectNote>
        <lido:objectNote lido:type="catalogue">#Bibliothèque | N° catalogue 1#</lido:objectNote>
    </lido:object>
</lido:relatedWork>
```

