
## [interact_shock](#interact_shock)

### Description
Handles interaction with shocking objects. If Mario touches an electrified enemy or hazard, he takes damage and may be stunned or shocked.
Useful for electric-themed enemies and obstacles

### Lua Example
`local integerValue = interact_shock(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_shock(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
