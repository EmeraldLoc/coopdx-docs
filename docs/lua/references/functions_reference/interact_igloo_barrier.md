
## [interact_igloo_barrier](#interact_igloo_barrier)

### Description
Handles interaction with the igloo barrier found in Snowman's Land. If Mario runs into the barrier, this function pushes him away and prevents passage without the vanish cap.
Useful for enforcing require-caps to access certain areas

### Lua Example
`local integerValue = interact_igloo_barrier(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_igloo_barrier(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
