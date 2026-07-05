
## [mario_obj_angle_to_object](#mario_obj_angle_to_object)

### Description
Calculates the angle between Mario and a specified object. Used for determining Mario's orientation relative to the object.
Useful for deciding directions between Mario and NPCs

### Lua Example
`local integerValue = mario_obj_angle_to_object(m, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`s16 mario_obj_angle_to_object(struct MarioState *m, struct Object *o);`
