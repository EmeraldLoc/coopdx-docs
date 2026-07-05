
## [mario_get_collided_object](#mario_get_collided_object)

### Description
Returns a collided object that matches a given interaction type from Mario's current collision data.
Useful for determining which object Mario has come into contact with

### Lua Example
`local objectValue = mario_get_collided_object(m, interactType)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *mario_get_collided_object(struct MarioState *m, u32 interactType);`
