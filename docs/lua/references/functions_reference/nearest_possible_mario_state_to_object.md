
## [nearest_possible_mario_state_to_object](#nearest_possible_mario_state_to_object)

### Description
Gets the nearest possible Mario to `obj` despite anything like bubbled state or enemy visibility

### Lua Example
`local marioStateValue = nearest_possible_mario_state_to_object(obj)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |

### Returns
- [MarioState](structs.md#MarioState)

### C Prototype
`struct MarioState* nearest_possible_mario_state_to_object(struct Object *obj);`
