---
description: Related Work Set
---

# relatedWorkSet \[Bibliography\]

### Description

#### LIDO

A wrapper for a object/work, group, collection, or series that is directly related to the object/work being recorded.

#### MNHA

This element contains the following elements:

* `relatedWork` \[Bibliography\]
* `relatedWorkRelType` \[Bibliography\]

### Attributes

_No attribute is currently defined for this element_

### Example

```markup
<lido:relatedWorkSet>
    <lido:relatedWork>     
        <lido:object>
            <lido:objectWebResource lido:formatResource="text/html">
                #Aleph LINK 1#
            </lido:objectWebResource>
            <lido:objectID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier" lido:source="a-z.lu">
                #Aleph ID 1#
            </lido:objectID>
            <lido:objectNote lido:type="book">#Bibliothèque | Réf. biblio. 1#</lido:objectNote>
            <lido:objectNote lido:type="page">#Bibliothèque | Page 1#</lido:objectNote>
            <lido:objectNote lido:type="illustration">#Bibliothèque | Ill. 1#</lido:objectNote>
            <lido:objectNote lido:type="catalogue">#Bibliothèque | N° catalogue 1#</lido:objectNote>
        </lido:object>
    </lido:relatedWork>
    <lido:relatedWorkRelType>
        <lido:term>Littérature en contexte</lido:term>
        <lido:term xml:lang="de">Literatur im Kontext</lido:term>
        <lido:term xml:lang="en">Literature in context</lido:term>
    </lido:relatedWorkRelType>
</lido:relatedWorkSet>
```



