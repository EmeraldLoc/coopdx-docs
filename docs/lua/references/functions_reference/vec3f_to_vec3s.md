
## [vec3f_to_vec3s](#vec3f_to_vec3s)

### Description
Converts a 3D floating-point vector `a` into a 3D short integer vector and stores the result in `dest`

### Lua Example
`local vec3sValue = vec3f_to_vec3s(dest, a)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3s](structs.md#Vec3s) |
| a | [Vec3f](structs.md#Vec3f) |

### Returns
- [Vec3s](structs.md#Vec3s)

### C Prototype
`Vec3sp vec3f_to_vec3s(VEC_OUT Vec3s dest, Vec3f a);`
