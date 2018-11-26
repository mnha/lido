---
description: Custody/Repository Location (Wrapper)
---

# 4.2.3 \| repositoryWrap

### Definition

Wrapper for Repository/ Location information.

This element contains the following element:

* `repositorySet`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:repositoryWrap>
    <lido:repositorySet
        lido:type="http://terminology.lido-schema.org/repositorySet_type/current_repository_or_location">
        <lido:repositoryName>
            <lido:legalBodyName>
                <lido:appellationValue>Musée national d'histoire et d'art Luxembourg</lido:appellationValue>
                <lido:appellationValue xml:lang="de">Nationalmuseum für Geschichte und Kunst Luxemburg</lido:appellationValue>
                <lido:appellationValue xml:lang="en">National Museum of History and Art Luxembourg</lido:appellationValue>
            </lido:legalBodyName>
            <lido:legalBodyWeblink>http://www.mnha.lu</lido:legalBodyWeblink>
        </lido:repositoryName>
        <lido:workID>
            #Inventory Number#
        </lido:workID>
        <lido:repositoryLocation>
            <lido:placeID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier">
                #Location in museum (Link)#
            </lido:placeID>
            <lido:namePlaceSet>
                <lido:appellationValue>#Objets | Empl. actuel (Text) (fr)#</lido:appellationValue>
                <lido:appellationValue xml:lang="de">#Objets | Empl. actuel (Text) (de)#</lido:appellationValue>
                <lido:appellationValue xml:lang="en">#Objets | Empl. actuel (Text) (en)#</lido:appellationValue>
            </lido:namePlaceSet>
        </lido:repositoryLocation>
    </lido:repositorySet>
</lido:repositoryWrap>
```

\_\_

