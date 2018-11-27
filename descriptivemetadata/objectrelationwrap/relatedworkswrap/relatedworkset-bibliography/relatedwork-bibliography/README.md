---
description: Related Work
---

# relatedWork \[Bibliography\]

{% hint style="info" %}
Still elements to be discussed
{% endhint %}

### Description

#### LIDO

Wrapper for the display and reference elements of a related object/work.

#### MNHA

This element contains the following elements

* displayObject
* object

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:relatedWork>
                        
    <!-- later
    <lido:displayObject>#Bibliography: display text#</lido:displayObject>
    <lido:displayObject>#Bibliography: display text#</lido:displayObject>
    <lido:displayObject>#Bibliography: display text#</lido:displayObject>
    -->
                        
    <lido:object>
        <lido:objectWebResource lido:formatResource="text/html">
            #Aleph LINK#
        </lido:objectWebResource>
        <lido:objectID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier" lido:source="a-z.lu">
            #Aleph ID#
        </lido:objectID>
    </lido:object>
</lido:relatedWork>
```

