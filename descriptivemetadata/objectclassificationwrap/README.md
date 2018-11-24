---
description: Object Classification Wrapper
---

# 4.1 \| objectClassificationWrap

### Description

#### LIDO

Wrapper for data classifying the object / work. Includes all classifying information about an object / work, such as: object / work type, style, genre, form, age, sex, and phase, or by how holding organization structures its collection \(e.g. fine art, decorative art, prints and drawings, natural science, numismatics, or local history\).

#### MNHA

This element contains the following elements:

* `objectWorkTypeWrap`
* `classificationWrap`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:objectClassificationWrap>
    <lido:objectWorkTypeWrap>
        <lido:objectWorkType>
            <lido:term>#Objets | Domaine(s) 1 (fr)#</lido:term>
            <lido:term xml:lang="de">#Objets | Domaine(s) 1 (de)#</lido:term>
            <lido:term xml:lang="en">#Objets | Domaine(s) 1 (en)#</lido:term>
        </lido:objectWorkType>
        <lido:objectWorkType>
            <lido:term>#Objets | Domaine(s) 2 (fr)#</lido:term>
            <lido:term xml:lang="de">#Objets | Domaine(s) 2 (de)#</lido:term>
            <lido:term xml:lang="en">#Objets | Domaine(s) 2 (en)#</lido:term>
        </lido:objectWorkType>
    </lido:objectWorkTypeWrap>
    <lido:classificationWrap>
        <lido:classification lido:type="collection">
            <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier">
                #Vocabulaire | Nom interne# <!-- format: collection#subcollection -->
            </lido:conceptID>
            <lido:term>#Objets | Collection (fr)#</lido:term>
            <lido:term xml:lang="de">#Objets | Collection (de)#</lido:term>
            <lido:term xml:lang="en">#Objets | Collection (en)#</lido:term>
        </lido:classification>
        <lido:classification lido:type="designation">
            <lido:term>#Objets | Dénomination (fr)#</lido:term>
            <lido:term xml:lang="de">#Objets | Dénomination (de)#</lido:term>
            <lido:term xml:lang="en">#Objets | Dénomination (en)#</lido:term>
        </lido:classification>
        <lido:classification lido:type="iconography">
            <lido:term>#Objets | Iconographie 1 (fr)#</lido:term>
            <lido:term xml:lang="de">#Objets | Iconographie 1 (de)#</lido:term>
            <lido:term xml:lang="en">#Objets | Iconographie 1 (en)#</lido:term>
        </lido:classification>
        <lido:classification lido:type="iconography">
            <lido:term>#Objets | Iconographie 2 (fr)#</lido:term>
            <lido:term xml:lang="de">#Objets | Iconographie 2 (de)#</lido:term>
            <lido:term xml:lang="en">#Objets | Iconographie 2 (en)#</lido:term>
        </lido:classification>
        <lido:classification lido:type="period_style_movement">
            <lido:term>#Objets | Époque / Mouv. 1 (fr)#</lido:term>
            <lido:term xml:lang="de">#Objets | Époque / Mouv. 1 (de)#</lido:term>
            <lido:term xml:lang="en">#Objets | Époque / Mouv. 1 (en)#</lido:term>
        </lido:classification>
        <lido:classification lido:type="period_style_movement">
            <lido:term>#Objets | Époque / Mouv. 2 (fr)#</lido:term>
            <lido:term xml:lang="de">#Objets | Époque / Mouv. 2 (de)#</lido:term>
            <lido:term xml:lang="en">#Objets | Époque / Mouv. 2 (en)#</lido:term>
        </lido:classification>
    </lido:classificationWrap>
</lido:objectClassificationWrap>
```

