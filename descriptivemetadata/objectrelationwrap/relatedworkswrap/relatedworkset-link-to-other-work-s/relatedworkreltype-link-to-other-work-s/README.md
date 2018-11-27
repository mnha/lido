---
description: Related Work Relationship Type
---

# relatedWorkRelType \[Link to other work\(s\)\]

### Description

#### LIDO

A term describing the nature of the relationship between the object / work at hand and the related entity.

Example values: part of, larger context for, model of, model for, study of, study forrendering of, copy of, related to. Indicate a term characterizing the relationship from the perspective of the currently described object / work towards the related object / work.

For implementation of the data, note that relationships are conceptually reciprocal, but the Relationship Type is often different on either side of the relationship \(e.g., one work is part of a second work, but from the point of view of the second record, the first work is the larger context for the second work\). Whether or not relationships are physically reciprocal as implemented in systems is a local decision.

#### MNHA

This element contains the following elements:

* `term` \[Link to other work\(s\)\]

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:relatedWorkRelType>
    <lido:term>#Objets | Réf. obj-obj. | Type (fr) 1#</lido:term>
    <lido:term xml:lang="de">#Objets | Réf. obj-obj. | Type (de) 1#</lido:term>
    <lido:term xml:lang="en">#Objets | Réf. obj-obj. | Type (en) 1#</lido:term>
</lido:relatedWorkRelType>
```

