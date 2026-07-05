
## [vec3f_set_magnitude](#vec3f_set_magnitude)

### Description
Sets the length (magnitude) of 3D floating-point vector `v`, while retaining its direction

### Lua Example
`local vec3fValue = vec3f_set_magnitude(v, mag)`

### Parameters
| Field | Type |
| ----- | ---- |
| v | [Vec3f](structs.md#Vec3f) |
| mag | `number` |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_set_magnitude(VEC_OUT Vec3f v, f32 mag);`
