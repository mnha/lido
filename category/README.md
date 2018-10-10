---
description: Category
---

# 3 \| category

### Description

#### LIDO

Indicates the category of which this item is an instance, preferably referring to CIDOC-CRM concept definitions.

CIDOC-CRM concept definitions are given at http://www.cidoccrm.org/crm-concepts/.

Data values in the sub-element term may often be: Man-Made Object \(with conceptID "http://www.cidoc-crm.org/crm-concepts/E22"\), Man-Made Feature \(http://www.cidoc-crm.org/crmconcepts/E25\), Collection \(http://www.cidoc-crm.org/crmconcepts/E78\).

### Attributes

_This element does not have attributes._

### Example

```markup
<lido:category>
    <lido:conceptID lido:type="http://terminology.lido-schema.org/identifier_type/uri">
        http://www.cidoc-crm.org/crm-concepts/#E22
    </lido:conceptID>
    <lido:term xml:lang="en">
        Man-Made Object
    </lido:term>
</lido:category>
```

