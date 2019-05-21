---
description: Event Date
---

# eventDate \[Beginning of existence\]

### Description

#### LIDO

Date specification of the event.

This element contains the following elements:

#### MNHA

This element contains the following elements:

* `displayDate`
* `date`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:eventDate>
    <lido:displayDate lido:label="date">#Objets | Dates/Siècle | Affichage [only date] (fr)#</lido:displayDate>
    <lido:displayDate xml:lang="de" lido:label="date">#Objets | Dates/Siècle | Affichage [only date] (de)#</lido:displayDate>
    <lido:displayDate xml:lang="en" lido:label="date">#Objets | Dates/Siècle | Affichage [only date] (en)#</lido:displayDate>
    <lido:displayDate lido:label="century">#Objets | Dates/Siècle | Affichage [only century] (fr)#</lido:displayDate>
    <lido:displayDate xml:lang="de" lido:label="century">#Objets | Dates/Siècle | Affichage [only century] (de)#</lido:displayDate>
    <lido:displayDate xml:lang="en" lido:label="century">#Objets | Dates/Siècle | Affichage [only century] (en)#</lido:displayDate>
    <lido:date>
        <lido:earliestDate>#Objets | Dates/Siècle | XXX (start)#</lido:earliestDate>
        <lido:latestDate>#Objets | Dates/Siècle | XXX (end)#</lido:latestDate>
    </lido:date>
</lido:eventDate>
```

