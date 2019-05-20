---
description: Classification Wrapper
---

# 4.1.2 \| classificationWrap

### Definition

#### LIDO

A wrapper for classification information.

#### MNHA

This element contains the following element:

* `classification`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:classificationWrap>
    <lido:classification lido:type="restriction">
        <lido:conceptID type="http://terminology.lido-schema.org/identifier_type/local_identifier">RESTRICTED</lido:conceptID>
    </lido:classification>
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
```



