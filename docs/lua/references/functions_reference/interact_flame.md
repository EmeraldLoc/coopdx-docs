
## [interact_flame](#interact_flame)

### Description
Handles interaction with flame objects. If Mario touches a flame and is not invulnerable or protected by certain caps, he takes damage and may be set on fire, causing a burning jump.
Useful for simulating fire damage and hazards in levels

### Lua Example
`local integerValue = interact_flame(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_flame(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
