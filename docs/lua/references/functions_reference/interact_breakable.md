
## [interact_breakable](#interact_breakable)

### Description
Handles interactions with breakable objects (e.g., breakable boxes or bob-ombs). If Mario hits the object with a valid attack (like a punch or kick), the object is destroyed or changes state.
Useful for managing collectible items hidden in breakable objects and level progression through destructible blocks or walls

### Lua Example
`local integerValue = interact_breakable(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_breakable(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
