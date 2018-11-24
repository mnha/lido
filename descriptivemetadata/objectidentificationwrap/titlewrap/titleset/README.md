---
description: Title or Object Name Set
---

# titleSet

### Definition

#### LIDO

Wrapper for one title or object name and its source information.

Mandatory. If there is no specific title, provide an object name in the appellation value. If there is more than one title, repeat the Title Set element.

For objects from natural, technical, cultural history e.g. the object name given here and the object type, recorded in the object / work type element are often identical.

### Attributes

No attribute is defined for the main title of an object. All other titles have the following attribute:

#### @type

This attribute contains the following default value:

`other`

### Example

```markup
<lido:titleSet>
    <lido:appellationValue>#Title (fr)#</lido:appellationValue>
    <lido:appellationValue xml:lang="de">#Title (de)#</lido:appellationValue>
    <lido:appellationValue xml:lang="en">#Title (en)#</lido:appellationValue>
</lido:titleSet>
<lido:titleSet lido:type="other">
    <lido:appellationValue>#Title (other) 1 (fr)#</lido:appellationValue>
    <lido:appellationValue xml:lang="de">#Title (other) 1 (de)#</lido:appellationValue>
    <lido:appellationValue xml:lang="en">#Title (other) 1 (en)#</lido:appellationValue>
</lido:titleSet>
<lido:titleSet lido:type="other">
    <lido:appellationValue>#Title (other) 2 (fr)#</lido:appellationValue>
    <lido:appellationValue xml:lang="de">#Title (other) 2 (de)#</lido:appellationValue>
    <lido:appellationValue xml:lang="en">#Title (other) 2 (en)#</lido:appellationValue>
</lido:titleSet>
```



