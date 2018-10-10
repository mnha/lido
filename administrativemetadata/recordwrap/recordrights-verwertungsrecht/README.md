---
description: Rights for Record
---

# 5.2.4 \| recordRights \[Droit d'exploitation\]

### Description

#### LIDO

Information about rights regarding the content provided in this LIDO record.

#### MNHA

This element contains the following elements:

* rightsType \[Droit d'exploitation\]
* rightsHolder \[Droit d'exploitation\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:recordRights>
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
</lido:recordRights>
```

