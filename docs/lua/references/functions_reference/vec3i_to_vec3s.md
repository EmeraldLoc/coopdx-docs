
## [vec3i_to_vec3s](#vec3i_to_vec3s)

### Description
Converts a 3D integer vector `a` into a 3D short integer vector and stores the result in `dest`

### Lua Example
`local vec3sValue = vec3i_to_vec3s(dest, a)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3s](structs.md#Vec3s) |
| a | [Vec3i](structs.md#Vec3i) |

### Returns
- [Vec3s](structs.md#Vec3s)

### C Prototype
`Vec3sp vec3i_to_vec3s(VEC_OUT Vec3s dest, Vec3i a);`
