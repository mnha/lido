---
description: Related Work Set
---

# relatedWorkSet \[Link to other work\(s\)\]

### Description

#### LIDO

A wrapper for a object / work, group, collection, or series that is directly related to the object / work being recorded.

#### MNHA

This element contains the following elements:

* `relatedWork` \[Link to other work\(s\)\]
* `relatedWorkRelType` \[Link to other work\(s\)\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:relatedWorkSet>
    <lido:relatedWork>
        <lido:displayObject>#Objet lié#</lido:displayObject>
        <lido:displayObject xml:lang="de">#Verknüpfte Objekte#</lido:displayObject>
        <lido:displayObject xml:lang="en">#Related work#</lido:displayObject>
        <lido:object>
            <lido:objectID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier" lido:source="MuseumPlus MNHA">
                #mnha[ID] 1#
            </lido:objectID>
        </lido:object>
    </lido:relatedWork>
    <lido:relatedWorkRelType>
        <lido:term>#Objets | Réf. obj-obj. | Type (fr) 1#</lido:term>
        <lido:term xml:lang="de">#Objets | Réf. obj-obj. | Type (de) 1#</lido:term>
        <lido:term xml:lang="en">#Objets | Réf. obj-obj. | Type (en) 1#</lido:term>
    </lido:relatedWorkRelType>
</lido:relatedWorkSet>
```

