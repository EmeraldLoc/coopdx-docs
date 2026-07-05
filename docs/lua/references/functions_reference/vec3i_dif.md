
## [vec3i_dif](#vec3i_dif)

### Description
Subtracts the components of the 3D integer vector `b` from the components of `a` and stores the result in `dest`

### Lua Example
`local vec3iValue = vec3i_dif(dest, a, b)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3i](structs.md#Vec3i) |
| a | [Vec3i](structs.md#Vec3i) |
| b | [Vec3i](structs.md#Vec3i) |

### Returns
- [Vec3i](structs.md#Vec3i)

### C Prototype
`Vec3ip vec3i_dif(VEC_OUT Vec3i dest, Vec3i a, Vec3i b);`
