---
description: Rights Type
---

# rightsType \[License\]

### Description

#### LIDO

The specific type of right being recorded.

For example: copyright, publication right, data protection right, trademark. Preferably taken from a published controlled value list.

#### MNHA

This rightsType Element names the license which lists the terms for reusing the metadata. A default license is used for all records.

{% hint style="info" %}
The use of the rightsType element for stating the license is semantically wrong but still commonly used in the LIDO community because there is not semantically correct way in LIDO 1.0.
{% endhint %}

This element contains the following elements:

* conceptID \[License\]
* term \[License\]

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:rightsType>
    <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">
        #The field does not exist yet#
    </lido:conceptID>
    <lido:term>#The field does not exist yet (fr)#</lido:term>
    <lido:term xml:lang="de">#The field does not exist yet (de)#</lido:term>
    <lido:term xml:lang="en">#The field does not exist yet (en)#</lido:term>
</lido:rightsType>
```

