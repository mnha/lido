---
description: Resource Wrapper
---

# 5.3 \| resourceWrap

### Description

#### LIDO

A wrapper for resources that are surrogates for an object / work, including digital images, videos or audio files that represent it in an online service.

#### MNHA

This element contains the following element:

* `resourceSet`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:resourceWrap>
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
    <lido:resourceSet lido:sortorder="2">
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
</lido:resourceWrap>
```

