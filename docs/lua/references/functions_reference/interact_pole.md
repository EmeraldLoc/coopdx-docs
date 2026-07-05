
## [interact_pole](#interact_pole)

### Description
Handles interaction with poles (e.g., climbing poles). If Mario runs into a vertical pole, he can grab it and start climbing.
Useful for platforming mechanics

### Lua Example
`local integerValue = interact_pole(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_pole(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
