# relatedWork \[Link to other work\(s\)\]

### Description

#### LIDO

Wrapper for the display and reference elements of a related object/work.

#### MNHA

This element contains the following elements:

* `displayObject` \[Link to other work\(s\)\]
* `object` \[Link to other work\(s\)\]

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:relatedWork>
    <lido:displayObject>#Objet lié#</lido:displayObject>
    <lido:displayObject xml:lang="de">#Verknüpfte Objekte#</lido:displayObject>
    <lido:displayObject xml:lang="en">#Related work#</lido:displayObject>
    <lido:object>
        <lido:objectID lido:type="http://terminology.lido-schema.org/identifier_type/local_identifier" lido:source="MuseumPlus MNHA">
            #mnha[ID] 1#
        </lido:objectID>
    </lido:object>
</lido:relatedWork>
```



