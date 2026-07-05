
## [obj_angle_to_point](#obj_angle_to_point)

### Description
Calculates the yaw angle from an object to a point

### Lua Example
`local integerValue = obj_angle_to_point(obj, pointX, pointZ)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |
| pointX | `number` |
| pointZ | `number` |

### Returns
- `integer`

### C Prototype
`s16 obj_angle_to_point(struct Object *obj, f32 pointX, f32 pointZ);`
