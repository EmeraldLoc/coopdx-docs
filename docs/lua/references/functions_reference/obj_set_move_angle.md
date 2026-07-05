
## [obj_set_move_angle](#obj_set_move_angle)

### Description
Sets an object's movement angle (pitch, yaw, roll)

### Lua Example
`obj_set_move_angle(obj, pitch, yaw, roll)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |
| pitch | `integer` |
| yaw | `integer` |
| roll | `integer` |

### Returns
- None

### C Prototype
`void obj_set_move_angle(struct Object *obj, s16 pitch, s16 yaw, s16 roll);`
