---
description: Rights for Resource
---

# 5.3.1.3 \| rightsResource \[Copyright Image\]

### Description

#### LIDO

Information about rights regarding the image or other resource.

Use this sub-element if the holder of the reproduction rights for the image/resource differs from the holder of rights for the work. See also Rights Work above. \(E.g., the work rights are " National Museum of African Art, Smithsonian Instituition \(Washing DC\), " but the image rights are "Photo Frank Khoury."\)

#### MNHA

This element contains the following elements:

* `rightsType` \[Copyright Image\]
* `rightsHolder` \[Copyright Image\]
* `creditLine` \[Copyright Image\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:rightsResource>
    <lido:rightsType>
        <lido:term>Copyright</lido:term>
        <lido:term xml:lang="de">Copyright</lido:term>
        <lido:term xml:lang="en">Copyright</lido:term>
    </lido:rightsType>
    <lido:rightsHolder>   
        <lido:legalBodyName>
            <lido:appellationValue>#Musée national d'histoire et d'art Luxembourg#</lido:appellationValue>
            <lido:appellationValue xml:lang="de">Nationalmuseum für Geschichte und Kunst Luxemburg</lido:appellationValue>
            <lido:appellationValue xml:lang="en">National Museum of History and Art Luxembourg</lido:appellationValue>
        </lido:legalBodyName>
        <lido:legalBodyweblink>http://www.mnha.lu</lido:legalBodyWeblink>
    </lido:rightsHolder>
    <lido:creditLine>#Multimédia | Auteur (fr)#</lido:creditLine>
    <lido:creditLine xml:lang="de">#Multimédia | Auteur (de)#</lido:creditLine>
    <lido:creditLine xml:lang="en">#Multimédia | Auteur (en)#</lido:creditLine>
</lido:rightsResource>
```

