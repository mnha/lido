---
description: Rights for Resource
---

# 5.3.1.3 \| rightsResource \[Copyright\]

### Description

#### LIDO

Information about rights regarding the image or other resource.

Use this sub-element if the holder of the reproduction rights for the image/resource differs from the holder of rights for the work. See also Rights Work above. \(E.g., the work rights are " National Museum of African Art, Smithsonian Instituition \(Washing DC\), " but the image rights are "Photo Frank Khoury."\)

#### MNHA

This element contains the following elements:

* rightsType \[Copyright\]
* rightsHolder \[Copyright\]
* creditLine \[Copyright\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:rightsResource>
    <lido:rightsType>
        <lido:term>Droit d'auteur</lido:term>
        <lido:term xml:lang="de">Urheberrecht</lido:term>
        <lido:term xml:lang="en">Copyright</lido:term>
    </lido:rightsType>
    <lido:rightsHolder>   
        <lido:legalBodyName>
            <lido:appellationValue>#Multimédia | Auteur#</lido:appellationValue>
        </lido:legalBodyName>
    </lido:rightsHolder>
    <lido:creditLine>#Multimédia | Copyright#</lido:creditLine>
</lido:rightsResource>
```

