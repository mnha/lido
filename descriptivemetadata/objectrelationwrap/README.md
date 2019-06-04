---
description: Object Relation Wrapper
---

# 4.4 \| objectRelationWrap

### Description

#### LIDO

Wrapper for infomation about related topics and works, collections, etc.

This includes visual contents and all associated entities the object is about.

#### MNHA

This element contains the following element:

* `relatedWorksWrap`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:objectRelationWrap>
    <lido:subjectWrap>
        <lido:subjectSet>
            <lido:subjectPlace>
                <lido:place>
                    <lido:partOfPlace lido:politicalEntity="country">
                        <lido:namePlaceSet>
                            <lido:appellationValue>#Objets | Réf. géo. [type=lieu représenté ; level 1] (fr)#</lido:appellationValue>
                            <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu représenté ; level 1] (de)#</lido:appellatoonValue>
                            <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu représenté ; level 1] (en)#</lido:appellationValue>
                        </lido:namePlaceSet>
                    </lido:partOfPlace>
                    <lido:partOfPlace lido:politicalEntity="city">
                        <lido:namePlaceSet>
                            <lido:appellationValue>#Objets | Réf. géo. [type=lieu représenté ; level 2] (fr)#</lido:appellationValue>
                            <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu représenté ; level 2] (de)#</lido:appellationValue>
                            <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu représenté ; level 2] (en)#</lido:appellationValue>
                        </lido:namePlaceSet>
                    </lido:partOfPlace>
                    <lido:partOfPlace lido:politicalEntity="place">
                        <lido:namePlaceSet>
                            <lido:appellationValue>#Objets | Réf. géo. [type=lieu représenté ; level 3] (fr)#</lido:appellationValue>
                            <lido:appellationValue xml:lang="de">#Objets | Réf. géo. [type=lieu représenté ; level 3] (de)#</lido:appellationValue>
                            <lido:appellationValue xml:lang="en">#Objets | Réf. géo. [type=lieu représenté ; level 3] (en)#</lido:appellationValue>
                        </lido:namePlaceSet>
                    </lido:partOfPlace>
                </lido:place>
            </lido:subjectPlace>
        </lido:subjectSet>
    </lido:subjectWrap>
    <lido:relatedWorksWrap>
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
        <lido:relatedWorkSet>
            <lido:relatedWork>
                <lido:displayObject>#Objet lié#</lido:displayObject>
                <lido:displayObject xml:lang="de">#Verknüpfte Objekte#</lido:displayObject>
                <lido:displayObject xml:lang="en">#Related work#</lido:displayObject>
                <lido:object>
                    <lido:objectID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier" lido:source="MuseumPlus MNHA">
                        #mnha[ID] 2#
                    </lido:objectID>
                </lido:object>
            </lido:relatedWork>
            <lido:relatedWorkRelType>
                <lido:term>#Objets | Réf. obj-obj. | Type (fr) 2#</lido:term>
                <lido:term xml:lang="de">#Objets | Réf. obj-obj. | Type (de) 2#</lido:term>
                <lido:term xml:lang="en">#Objets | Réf. obj-obj. | Type (en) 2#</lido:term>
            </lido:relatedWorkRelType>
        </lido:relatedWorkSet>
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
                    <lido:objectNote lido:type="page">#Objets | Biblographie | Page 1#</lido:objectNote>
                    <lido:objectNote lido:type="illustration">#Objets | Biblographie | Ill. 1#</lido:objectNote>
                    <lido:objectNote lido:type="catalogue">#Objets | Biblographie | N° catalogue 1#</lido:objectNote>
                </lido:object>
            </lido:relatedWork>
            <lido:relatedWorkRelType>
                <lido:term>Littérature en contexte</lido:term>
                <lido:term xml:lang="de">Literatur im Kontext</lido:term>
                <lido:term xml:lang="en">Literature in context</lido:term>
            </lido:relatedWorkRelType>
        </lido:relatedWorkSet>
        <lido:relatedWorkSet>
            <lido:relatedWork>
                <lido:object>
                    <lido:objectWebResource lido:formatResource="text/html">
                        #Aleph LINK 2#
                    </lido:objectWebResource>
                    <lido:objectID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier" lido:source="a-z.lu">
                        #Aleph ID 2#
                    </lido:objectID>
                    <lido:objectNote lido:type="book">#Bibliothèque | Réf. biblio. 2#</lido:objectNote>
                    <lido:objectNote lido:type="page">#Objets | Biblographie | Page 2#</lido:objectNote>
                    <lido:objectNote lido:type="illustration">#Objets | Biblographie | Ill. 2#</lido:objectNote>
                    <lido:objectNote lido:type="catalogue">#Objets | Biblographie | N° catalogue 2#</lido:objectNote>
                </lido:object>
            </lido:relatedWork>
            <lido:relatedWorkRelType>
                <lido:term>Littérature en contexte</lido:term>
                <lido:term xml:lang="de">Literatur im Kontext</lido:term>
                <lido:term xml:lang="en">Literature in context</lido:term>
            </lido:relatedWorkRelType>
        </lido:relatedWorkSet>
    </lido:relatedWorksWrap>
</lido:objectRelationWrap>
```

