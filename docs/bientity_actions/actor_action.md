---
title: Actor Action (Bi-Entity Action)
date: 2021-10-07
---
# Actor Action

[Bi-Entity Action](../bientity_actions.md).

Executes an entity action as the actor of the action, simulating a regular entity action. This is mainly to be used when there is only a bientity action field.

Type ID: `origins:actor_action`

### Fields

Field  | Type | Default | Description
-------|------|---------|-------------
`entity_action` | [Action](../entity_actions.md) | | The action which might be executed.

### Example

```json
"bientity_action": {
    "type": "origins:actor_action",
    "entity_action": {
        "type": "origins:set_on_fire",
        "duration": 5
    }
}
```

This will set the actor of the action on fire for 5 seconds.