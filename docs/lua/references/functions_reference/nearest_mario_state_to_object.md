
## [nearest_mario_state_to_object](#nearest_mario_state_to_object)

### Description
Gets the nearest active Mario who isn't bubbled to `obj`

### Lua Example
`local marioStateValue = nearest_mario_state_to_object(obj)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |

### Returns
- [MarioState](structs.md#MarioState)

### C Prototype
`struct MarioState* nearest_mario_state_to_object(struct Object *obj);`
