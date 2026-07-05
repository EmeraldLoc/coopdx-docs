
## [interact_strong_wind](#interact_strong_wind)

### Description
Handles interaction with strong wind gusts. These gusts push Mario back, often knocking him off platforms or sending him flying backwards.
Useful for environmental wind hazards

### Lua Example
`local integerValue = interact_strong_wind(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_strong_wind(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
