---
description: Related Work Set
---

# relatedWorkSet \[Bibliography\]

{% hint style="info" %}
Still elements to be discussed!
{% endhint %}

### Description

#### LIDO

A wrapper for a object/work, group, collection, or series that is directly related to the object/work being recorded.

#### MNHA

This element contains the following elements:

* `relatedWork` \[Bibliography\]
* `relatedWorkRelType` \[Bibliography\]

### Attributes

_No attribute is currently defined for this element_

### Example

```markup
<lido:relatedWorkSet>
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
    <lido:relatedWorkRelType>
        <lido:term>Littérature en contexte</lido:term>
        <lido:term xml:lang="de">Literatur im Kontext</lido:term>
        <lido:term xml:lang="en">Literature in context</lido:term>
    </lido:relatedWorkRelType>
</lido:relatedWorkSet>
```



