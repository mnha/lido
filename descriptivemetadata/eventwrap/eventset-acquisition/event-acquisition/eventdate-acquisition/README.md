---
description: Event Date
---

# eventDate \[Acquisition\]

### Description

#### LIDO

Date specification of the event.

#### MNHA

This element contains the following elements:

* `displayDate`
* `date`

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:eventDate>
    <lido:displayDate>#Objets | Date d'acq.#</lido:displayDate>
    <lido:date>
        <lido:earliestDate>#Acquisition date ISO 8601#</lido:earliestDate>
        <lido:latestDate>#Acquisition date ISO 8601#</lido:latestDate>
    </lido:date>
</lido:eventDate>
```

