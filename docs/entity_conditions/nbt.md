---
title: NBT (Entity Condition)
date: 2021-10-02
---

# NBT

[Entity Condition](../entity_conditions.md)

Checks the entity's NBT.

Type ID: `origins:nbt`

!!! caution

    This condition is only effective server-side. That means client-side power types such as [`origins:climbing`](../power_types/climbing.md), [`origins:entity_glow`](../power_types/entity_glow.md), [`origins:shader`](../power_types/shader.md), etc. won't work with this.    

### Fields

Field | Type | Default | Description
------|------|---------|-------------
`nbt` | [String](../data_types/string.md) | | The NBT data to check for.

### Example
```json
"condition": {
    "type": "origins:nbt",
    "nbt": "{Tags: ['example_tag']}"
}
```
This example checks if the entity has the `example_tag` added via `/tag` or by modifying the entity's `Tags` NBT string list.