---
description: Resource Set
---

# 5.3.1 \| resourceSet

### Description

#### LIDO

Contains sub-elements for a structured resource description.

Provides identification of a surrogate of the object / work including digital images, slides, transparencies, photographs, audio, video and moving images, but excluding items that are considered object / works in their own right.

For such as drawings, prints, paintings, or photographs considered art, and other works that themselves contain representations of other works, use Related Works and/or Subjects.

#### MNHA

This element contains the following elements:

* resourceID
* resourceDescription
* rightsResource \[Copyright Image\]
* rightsResource \[License\]

### Attributes

#### @sortorder

This attribute contains an integer indicating the display order of the resources \(images\).

{% hint style="info" %}
The order should correspond to the element order, because the Goobi Viewer does not evaluate the sortorder attribute at the moment and uses the element order as display order instead.
{% endhint %}

### Example

```markup
<lido:resourceSet lido:sortorder="1">
    <lido:resourceID
        lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier" 
        lido:source="MuseumPlus MNHA">
        #filename.jpg#
    </lido:resourceID>
    <lido:resourceDescription>#Multimédia | Type (fr)#</lido:resourceDescription>
    <lido:resourceDescription xml:lang="de">#Multimédia | Type (de)#</lido:resourceDescription>
    <lido:resourceDescription xml:lang="en">#Multimédia | Type (en)#</lido:resourceDescription>
    <lido:rightsResource>
        <lido:rightsType>
            <lido:term>Copyright</lido:term>
            <lido:term xml:lang="de">Copyright</lido:term>
            <lido:term xml:lang="en">Copyright</lido:term>
        </lido:rightsType>
        <lido:rightsHolder>
            <lido:legalBodyName>
                <lido:appellationValue>Musée national d'histoire et d'art Luxembourg</lido:appellationValue>
                <lido:appellationValue xml:lang="de">Nationalmuseum für Geschichte und Kunst Luxemburg</lido:appellationValue>
                <lido:appellationValue xml:lang="en">National Museum of History and Art Luxembourg</lido:appellationValue>
            </lido:legalBodyName>
            <lido:legalBodyWeblink>http://www.mnha.lu</lido:legalBodyWeblink>
        </lido:rightsHolder>
        <lido:creditLine>#Multimédia | Auteur (fr)#</lido:creditLine>
        <lido:creditLine xml:lang="de">#Multimédia | Auteur (de)#</lido:creditLine>
        <lido:creditLine xml:lang="en">#Multimédia | Auteur (en)#</lido:creditLine>
    </lido:rightsResource>
    <lido:rightsResource>
        <lido:rightsType>
            <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">#URI#</lido:conceptID>
            <lido:term>#URI display text (fr)#</lido:term>
            <lido:term xml:lang="de">#URI display text (de)#</lido:term>
            <lido:term xml:lang="en">#URI display text (en)#</lido:term>   
        </lido:rightsType>  
    </lido:rightsResource>
</lido:resourceSet>
```

