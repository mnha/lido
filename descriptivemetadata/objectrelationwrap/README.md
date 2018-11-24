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

* relatedWorksWrap

### Attributes

_This element does not have attributes._

### Example

```text
<lido:objectRelationWrap>
            <lido:relatedWorksWrap>
                
                <!-- relatedWorkSet [Link to other work(s)] -->
                
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
                
                <!-- relatedWorkSet [Bibliography] -->
                
                <lido:relatedWorkSet>
                    <lido:relatedWork>
                        
                        <!-- later
                        <lido:displayObject>#Bibliography: display text#</lido:displayObject>
                        <lido:displayObject>#Bibliography: display text#</lido:displayObject>
                        <lido:displayObject>#Bibliography: display text#</lido:displayObject>
                        -->
                        
                        <lido:object>
                            <lido:objectWebResource lido:formatResource="text/html">
                                #Aleph LINK#
                            </lido:objectWebResource>
                            <lido:objectID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier" lido:source="a-z.lu">
                                #Aleph ID#
                            </lido:objectID>
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

