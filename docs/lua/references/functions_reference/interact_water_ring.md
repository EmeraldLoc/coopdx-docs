
## [interact_water_ring](#interact_water_ring)

### Description
Handles interactions with water rings that heal Mario. Passing through water rings increases his health counter.
Useful for underwater stages

### Lua Example
`local integerValue = interact_water_ring(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_water_ring(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
