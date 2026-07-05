
## [vec3i_set_magnitude](#vec3i_set_magnitude)

### Description
Sets the length (magnitude) of 3D integer vector `v`, while retaining its direction

### Lua Example
`local vec3iValue = vec3i_set_magnitude(v, mag)`

### Parameters
| Field | Type |
| ----- | ---- |
| v | [Vec3i](structs.md#Vec3i) |
| mag | `number` |

### Returns
- [Vec3i](structs.md#Vec3i)

### C Prototype
`Vec3ip vec3i_set_magnitude(VEC_OUT Vec3i v, f32 mag);`
