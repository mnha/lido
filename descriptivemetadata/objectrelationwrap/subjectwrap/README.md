---
description: Subject Wrapper
---

# subjectWrap

### Description

#### LIDO

A wrapper for Subject information. This may be the visual content \(e.g. the iconography of a painting\) or what the object is about.

#### MNHA

This element contains the following element:

* `subjectSet`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:subjectWrap>
    <lido:subjectSet>
        <lido:subjectPlace>
            <lido:place>
                <lido:partofPlace lido:politicalEntity="country">
                    <lido:namePlaceSet>
                        <lido:appellationValue>#Objets | Réf. géo. | [type=lieu représenté ; level=1] (fr)#</lido:apellationValue>
                        <lido:appellationValue xml:lang="de">#Objets | Réf. géo. | [type=lieu représenté ; level=1] (de)#</lido:apellationValue>
                        <lido:appellationValue xml:lang="en">#Objets | Réf. géo. | [type=lieu représenté ; level=1] (en)#</lido:apellationValue>
                    </lido:namePlaceSet>
                <lido:partofPlace lido:politicalEntity="city">
                    <lido:namePlaceSet>
                        <lido:appellationValue>#Objets | Réf. géo. | [type=lieu représenté ; level=2] (fr)#</lido:apellationValue>
                        <lido:appellationValue xml:lang="de">#Objets | Réf. géo. | [type=lieu représenté ; level=2] (de)#</lido:apellationValue>
                        <lido:appellationValue xml:lang="en">#Objets | Réf. géo. | [type=lieu représenté ; level=2] (en)#</lido:apellationValue>
                    </lido:namePlaceSet>
                <lido:partofPlace lido:politicalEntity="place">
                    <lido:namePlaceSet>
                        <lido:appellationValue>#Objets | Réf. géo. | [type=lieu représenté ; level=3] (fr)#</lido:apellationValue>
                        <lido:appellationValue xml:lang="de">#Objets | Réf. géo. | [type=lieu représenté ; level=3] (de)#</lido:apellationValue>
                        <lido:appellationValue xml:lang="en">#Objets | Réf. géo. | [type=lieu représenté ; level=3] (en)#</lido:apellationValue>
                    </lido:namePlaceSet>
                </lido:partofPlace>
                </lido:partofPlace>
                </lido:partofPlace>
            </lido:place>
        </lido:subjectPlace>
    </lido:subjectSet>
</lido:subjectWrap>
```

