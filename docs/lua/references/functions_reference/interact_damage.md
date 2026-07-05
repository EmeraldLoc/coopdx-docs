
## [interact_damage](#interact_damage)

### Description
Handles damaging interactions from various objects (e.g., enemies, hazards). If Mario takes damage, it applies knockback and reduces health.
Useful for enemy attacks, environmental hazards, and managing damage related behaviors

### Lua Example
`local integerValue = interact_damage(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_damage(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
