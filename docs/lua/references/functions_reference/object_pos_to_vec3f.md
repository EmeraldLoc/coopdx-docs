
## [object_pos_to_vec3f](#object_pos_to_vec3f)

### Description
Converts an object's position to a `Vec3f` format.
Useful for aligning object behaviors or interactions with the camera system

### Lua Example
`object_pos_to_vec3f(dst, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| dst | [Vec3f](structs.md#Vec3f) |
| o | [Object](structs.md#Object) |

### Returns
- None

### C Prototype
`void object_pos_to_vec3f(VEC_OUT Vec3f dst, struct Object *o);`
