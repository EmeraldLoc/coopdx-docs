
## [nearest_interacting_mario_state_to_object](#nearest_interacting_mario_state_to_object)

### Description
Gets the nearest interacting Mario to `obj`

### Lua Example
`local marioStateValue = nearest_interacting_mario_state_to_object(obj)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |

### Returns
- [MarioState](structs.md#MarioState)

### C Prototype
`struct MarioState *nearest_interacting_mario_state_to_object(struct Object *obj);`
