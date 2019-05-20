---
description: Classification
---

# classification

### Definition

#### LIDO

Concepts used to categorize an object / work by grouping it together with others on the basis of similar characteristics.

The category belongs to a systematic scheme \(classification\) which groups objects of similar characteristics according to uniform aspects. This grouping / classification may be done according to material, form, shape, function, region of origin, cultural context, or historical or stylistic period. In addition to this systematic grouping it may also be done according to organizational divisions within a museum \(e.g., according to the collection structure of a museum\). If the object / work is assigned to multiple classifications, repeat this element. Preferably taken from a published controlled vocabulary.

#### MNHA

This element contains the following element:

* `conceptID`
* `term`

### Attributes

#### @type

This attribute contains the following values to specify the content of the subelement term:

`RESTRICTED`

The content of the sub-element term is hardcoded in the xml file

`collection`

The content of the sub-element term is from the MuseumPlus field "Objets \| Collection"

`designation`

The content of the sub-element term is from the MuseumPlus field "Objets \| Dénomination"

`iconography`

The content of the sub-element term is from the MuseumPlus field "Objets \| Iconographie"

`period_style_movement`

The content of the sub-element term is from the MuseumPlus field "Objets \| Époque \| Mouv."

### Example

```markup
<lido:classification lido:type="restriction">
    <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier">RESTRICTED</lido:conceptID>
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
```

