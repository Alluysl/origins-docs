---
title: Shaking (Power Type)
date: 2021-04-08
---
# Shaking

[Power Type](../power_types.md).

Makes the player shake, similar to a strider out of lava or a zombie undergoing conversion.

Type ID: `origins:disable_regen`

### Fields

_None._

### Example
```json
{
  	"type": "origins:shaking",
  	"condition": {
    	"type": "origins:on_fire"
  	}
}
```
This power makes the player shake when they are not burning.