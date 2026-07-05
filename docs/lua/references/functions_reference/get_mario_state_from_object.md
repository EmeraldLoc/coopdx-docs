
## [get_mario_state_from_object](#get_mario_state_from_object)

### Description
Gets the MarioState corresponding to the provided object if the object is a Mario object

### Lua Example
`local marioStateValue = get_mario_state_from_object(o)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |

### Returns
- [MarioState](structs.md#MarioState)

### C Prototype
`struct MarioState *get_mario_state_from_object(struct Object *o);`
