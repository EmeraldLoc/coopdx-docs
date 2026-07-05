
## [take_damage_and_knock_back](#take_damage_and_knock_back)

### Description
Handles the logic of Mario taking damage and being knocked back by a damaging object.
Decreases Mario's health, sets his knockback state, and triggers appropriate sound and camera effects.
Useful for implementing enemy attacks, hazards, and ensuring Mario receives proper feedback upon taking damage

### Lua Example
`local integerValue = take_damage_and_knock_back(m, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 take_damage_and_knock_back(struct MarioState *m, struct Object *o);`
