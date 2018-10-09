---
description: Title or Object Name Set
---

# titleSet

### Definition

Wrapper for one title or object name and its source information.

Mandatory. If there is no specific title, provide an object name in the appellation value. If there is more than one title, repeat the Title Set element.

For objects from natural, technical, cultural history e.g. the object name given here and the object type, recorded in the object / work type element are often identical.

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:titleSet>
    <lido:appellationValue>#Title (fr)#</lido:appellationValue>
    <lido:appellationValue xml:lang="en">#Title (en)#</lido:appellationValue>
    <lido:appellationValue xml:lang="de">#Title (de)#</lido:appellationValue>
</lido:titleSet>
```



