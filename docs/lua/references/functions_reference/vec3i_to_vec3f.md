
## [vec3i_to_vec3f](#vec3i_to_vec3f)

### Description
Converts a 3D integer vector `a` into a 3D floating-point vector and stores the result in `dest`

### Lua Example
`local vec3fValue = vec3i_to_vec3f(dest, a)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| a | [Vec3i](structs.md#Vec3i) |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3i_to_vec3f(VEC_OUT Vec3f dest, Vec3i a);`
