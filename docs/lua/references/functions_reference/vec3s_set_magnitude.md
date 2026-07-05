
## [vec3s_set_magnitude](#vec3s_set_magnitude)

### Description
Sets the length (magnitude) of 3D short integer vector `v`, while retaining its direction

### Lua Example
`local vec3sValue = vec3s_set_magnitude(v, mag)`

### Parameters
| Field | Type |
| ----- | ---- |
| v | [Vec3s](structs.md#Vec3s) |
| mag | `number` |

### Returns
- [Vec3s](structs.md#Vec3s)

### C Prototype
`Vec3sp vec3s_set_magnitude(VEC_OUT Vec3s v, f32 mag);`
