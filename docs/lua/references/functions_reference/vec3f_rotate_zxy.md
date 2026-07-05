
## [vec3f_rotate_zxy](#vec3f_rotate_zxy)

### Description
Rotates the 3D floating-point vector `v` by the angles specified in the 3D signed-integer vector `rotate`, applying the rotations in the order Z, then X, then Y. The rotated vector replaces `v`

### Lua Example
`local vec3fValue = vec3f_rotate_zxy(v, rotate)`

### Parameters
| Field | Type |
| ----- | ---- |
| v | [Vec3f](structs.md#Vec3f) |
| rotate | [Vec3s](structs.md#Vec3s) |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_rotate_zxy(VEC_OUT Vec3f v, Vec3s rotate);`
