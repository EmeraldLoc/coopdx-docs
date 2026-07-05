
## [obj_rotate_towards_point](#obj_rotate_towards_point)

### Description
Rotates an object toward a specific point in 3D space.
Gradually updates the object's pitch and yaw angles to face the target

### Lua Example
`obj_rotate_towards_point(o, point, pitchOff, yawOff, pitchDiv, yawDiv)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| point | [Vec3f](structs.md#Vec3f) |
| pitchOff | `integer` |
| yawOff | `integer` |
| pitchDiv | `integer` |
| yawDiv | `integer` |

### Returns
- None

### C Prototype
`void obj_rotate_towards_point(struct Object *o, Vec3f point, s16 pitchOff, s16 yawOff, s16 pitchDiv, s16 yawDiv);`
