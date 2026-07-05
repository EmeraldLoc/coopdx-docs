
## [vec3f_to_vec3i](#vec3f_to_vec3i)

### Description
Converts a 3D floating-point vector `a` into a 3D integer vector and stores the result in `dest`

### Lua Example
`local vec3iValue = vec3f_to_vec3i(dest, a)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3i](structs.md#Vec3i) |
| a | [Vec3f](structs.md#Vec3f) |

### Returns
- [Vec3i](structs.md#Vec3i)

### C Prototype
`Vec3ip vec3f_to_vec3i(VEC_OUT Vec3i dest, Vec3f a);`
