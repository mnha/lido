---
description: Event Wrapper
---

# 4.3 \| eventWrap

### Description

#### LIDO

Wrapper for event sets.

#### MNHA

This element contains the following elements:

* `eventSet` \[Beginning of existence\]
* `eventSet` \[Use\]
* `eventSet` \[Acquisition\]

This LIDO schema uses three different types of events. They are described separately for a better overview. The element names are suffixed with their according English eventType/term.

An eventWrap element must contain one or more eventSet elements.

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:eventWrap>
    <!-- eventSet [Beginning of existence] -->
    <lido:eventSet>
        ...
    </lido:eventSet>
    <!-- eventSet [Use] -->
    <lido:eventSet>
        ...
    </lido:eventSet>
    <!-- eventSet [Acquisition] --> <!-- only used for donations and bequests -->
    <lido:eventSet>
        ...
    </lido:eventSet>
</lido:eventWrap>
```



