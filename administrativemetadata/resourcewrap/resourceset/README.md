---
description: Resource Set
---

# resourceSet

### Description

#### LIDO

Contains sub-elements for a structured resource description.

Provides identification of a surrogate of the object / work including digital images, slides, transparencies, photographs, audio, video and moving images, but excluding items that are considered object / works in their own right.

For such as drawings, prints, paintings, or photographs considered art, and other works that themselves contain representations of other works, use Related Works and/or Subjects.

#### MNHA

This element contains the following elements:

* resourceID
* resourceDescription
* rightsResource \[Urheberrecht\]
* rightsResource \[Verwertungsrecht\]
* rightsResource \[License\]

### Attributes

#### @sortorder

This attribute contains an integer indicating the display order of the resources \(images\).

{% hint style="info" %}
The order should correspond to the element order, because the Goobi Viewer does not evaluate the sortorder attribute at the moment and uses the element order as display order instead.
{% endhint %}

### Example

```text
<lido:resourceSet lido:sortorder="1">
<lido:resourceID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier" lido:source="MuseumPlus MNHA">#local filename#</lido:resourceID>
<lido:resourceDescription>#Image Type#</lido:resourceDescription>
<lido:rightsResource>
<!-- TODO Bezeichnung für Urheberrecht -->
<lido:rightsType>
<lido:term>TODO</lido:term>
</lido:rightsType>
<lido:rightsHolder>   
<lido:legalBodyName>
<lido:appellationValue>#Name of the photographer#</lido:appellationValue>
</lido:legalBodyName>
</lido:rightsHolder>
<lido:creditLine>#Copyright of photo#</lido:creditLine>
</lido:rightsResource>
<lido:rightsResource>
<!-- TODO Bezeichnung für Verwertungsrecht -->
<lido:rightsType>
<lido:term>TODO</lido:term>
</lido:rightsType>
<lido:rightsHolder>
<lido:legalBodyName>
<lido:appellationValue xml:lang="en">National Museum of History and Art</lido:appellationValue>
<lido:appellationValue>Musée national d'histoire et d'art Luxembourg</lido:appellationValue>
<lido:appellationValue xml:lang="de">Nationalmuseum für Geschichte und Kunst</lido:appellationValue>
</lido:legalBodyName>
<lido:legalBodyWeblink>http://www.mnha.lu</lido:legalBodyWeblink>
</lido:rightsHolder>
</lido:rightsResource>
<lido:rightsResource>
<lido:rightsType>
<lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">#Licence URI#</lido:conceptID>
<lido:term xml:lang="en">#Licence Name#</lido:term>
<lido:term>#Licence Name (French)#</lido:term>
<lido:term xml:lang="de">#Licence Name (German)#</lido:term>
</lido:rightsType>  
</lido:rightsResource>
</lido:resourceSet>
```

