---
description: Rights for Resource
---

# 5.3.1.4 \| rightsResource \[License\]

### Description

#### LIDO

Information about rights regarding the image or other resource.

Use this sub-element if the holder of the reproduction rights for the image/resource differs from the holder of rights for the work. See also Rights Work above. \(E.g., the work rights are " National Museum of African Art, Smithsonian Instituition \(Washing DC\), " but the image rights are "Photo Frank Khoury."\)

#### MNHA

This element contains the following elements:

* `rightsType` \[License\]

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:rightsResource>
    <lido:rightsType>
        <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">#URI#</lido:conceptID>
        <lido:term>#URI display text (fr)#</lido:term>
        <lido:term xml:lang="de">#URI display text (de)#</lido:term>
        <lido:term xml:lang="en">#URI display text (en)#</lido:term>
    </lido:rightsType>
</lido:rightsResource>
```

