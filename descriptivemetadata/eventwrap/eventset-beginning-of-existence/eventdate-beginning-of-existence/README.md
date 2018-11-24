---
description: Event Date
---

# eventDate \[Beginning of existence\]

### Description

#### LIDO

Date specification of the event.

This element contains the following elements:

#### MNHA

* displayDate
* date

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:eventDate>
    <lido:displayDate>#Objets | Dates/Siècle | Affichage (fr)#</lido:displayDate>
    <lido:displayDate xml:lang="de">#Objets | Dates/Siècle | Affichage (de)#</lido:displayDate>
    <lido:displayDate xml:lang="en">#Objets | Dates/Siècle | Affichage (en)#</lido:displayDate>
    <lido:date>
        <lido:earliestDate>#Objets | Dates/Siècle | XXX (start)#</lido:earliestDate>
        <lido:latestDate>#Objets | Dates/Siècle | XXX (end)#</lido:latestDate>
    </lido:date>
</lido:eventDate>
```

