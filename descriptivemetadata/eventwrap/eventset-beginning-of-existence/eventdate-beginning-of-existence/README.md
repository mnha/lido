---
description: Event Date
---

# eventDate \[Beginning of existence\]

### Definition

Date specification of the event.

This element contains the following elements:

* displayDate
* date

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:eventDate>
    <lido:displayDate>#Date(s): Display (fr)#</lido:displayDate>
    <lido:displayDate xml:lang="de">#Date(s): Display (de)#</lido:displayDate>
    <lido:displayDate xml:lang="en">#Date(s): Display (en)#</lido:displayDate>
    <lido:date>
        <lido:earliestDate>#Date (start)#</lido:earliestDate>
        <lido:latestDate>#Date (end)#</lido:latestDate>
    </lido:date>
</lido:eventDate>
```

