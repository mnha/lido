---
description: Rights for Resource
---

# 5.3.1.4 \| rightsResource \[Droit d'exploitation\]

### Description

#### LIDO

Information about rights regarding the image or other resource.

Use this sub-element if the holder of the reproduction rights for the image/resource differs from the holder of rights for the work. See also Rights Work above. \(E.g., the work rights are " National Museum of African Art, Smithsonian Instituition \(Washing DC\), " but the image rights are "Photo Frank Khoury."\)

#### MNHA

This element contains the following elements:

* rightsType \[Droit d'exploitation\]
* rightsHolder \[Droit d'exploitation\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:rightsResource>
    <lido:rightsType>
        <lido:term>Droit d'exploitation</lido:term>
        <lido:term xml:lang="de">Verwertungsrecht</lido:term>
        <lido:term xml:lang="en">Exploitation right</lido:term>
    </lido:rightsType>
    <lido:rightsHolder>
        <lido:legalBodyName>
            <lido:appellationValue>Musée national d'histoire et d'art Luxembourg</lido:appellationValue>
            <lido:appellationValue xml:lang="de">Nationalmuseum für Geschichte und Kunst Luxemburg</lido:appellationValue>
            <lido:appellationValue xml:lang="en">National Museum of History and Art Luxembourg</lido:appellationValue>
        </lido:legalBodyName>
        <lido:legalBodyWeblink>http://www.mnha.lu</lido:legalBodyWeblink>
    </lido:rightsHolder>
</lido:rightsResource>
```

