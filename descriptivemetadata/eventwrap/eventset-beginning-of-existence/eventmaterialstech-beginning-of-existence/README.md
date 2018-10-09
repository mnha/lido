---
description: Event Materials/Technique
---

# eventMaterialsTech \[Beginning of existence\]

### Definition

Indicates the substances or materials used within the event \(e.g. the creation of an object / work\), as well as any implements, production or manufacturing techniques, processes, or methods incorporated.

Will be used most often within a production event, but also others such as excavation, restoration, etc.

This element is repeated for multiple techniques / materials.

This element contains the following element:

* displayMaterialsTech

### Attributes

_No attribute is currently defined for this element._

### Example

```markup
<lido:eventMaterialsTech>
    <lido:displayMaterialsTech>#Technique | Material 1 (fr)#</lido:displayMaterialsTech>
    <lido:displayMaterialsTech xml:lang="de">#Technique | Material 1 (de)#</lido:displayMaterialsTech>
    <lido:displayMaterialsTech xml:lang="en">#Technique | Material 1 (en)#</lido:displayMaterialsTech>
</lido:eventMaterialsTech>
<lido:eventMaterialsTech>
    <lido:displayMaterialsTech>#Technique | Material 2 (fr)#</lido:displayMaterialsTech>
    <lido:displayMaterialsTech xml:lang="de">#Technique | Material 2 (de)#</lido:displayMaterialsTech>
    <lido:displayMaterialsTech xml:lang="en">#Technique | Material 2 (en)#</lido:displayMaterialsTech>
</lido:eventMaterialsTech>
```

