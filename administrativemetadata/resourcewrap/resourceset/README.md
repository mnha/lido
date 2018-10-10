---
description: Resource Set
---

# 5.3.1 \| resourceSet

### Description

#### LIDO

Contains sub-elements for a structured resource description.

Provides identification of a surrogate of the object / work including digital images, slides, transparencies, photographs, audio, video and moving images, but excluding items that are considered object / works in their own right.

For such as drawings, prints, paintings, or photographs considered art, and other works that themselves contain representations of other works, use Related Works and/or Subjects.

#### MNHA

This element contains the following elements:

* resourceID
* resourceDescription
* rightsResource \[Urheberrecht\]
* rightsResource \[Verwertungsrecht\]
* rightsResource \[License\]

### Attributes

#### @sortorder

This attribute contains an integer indicating the display order of the resources \(images\).

{% hint style="info" %}
The order should correspond to the element order, because the Goobi Viewer does not evaluate the sortorder attribute at the moment and uses the element order as display order instead.
{% endhint %}

### Example

```text

```

