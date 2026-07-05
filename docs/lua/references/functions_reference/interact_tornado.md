
## [interact_tornado](#interact_tornado)

### Description
Handles interaction with tornados. If Mario touches a tornado, he enters a spinning twirl action, losing control temporarily.
Useful for desert levels or areas where environmental hazards lift Mario into the air

### Lua Example
`local integerValue = interact_tornado(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_tornado(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
