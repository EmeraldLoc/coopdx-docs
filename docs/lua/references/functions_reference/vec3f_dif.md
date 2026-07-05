
## [vec3f_dif](#vec3f_dif)

### Description
Subtracts the components of the 3D floating-point vector `b` from the components of `a` and stores the result in `dest`

### Lua Example
`local vec3fValue = vec3f_dif(dest, a, b)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| a | [Vec3f](structs.md#Vec3f) |
| b | [Vec3f](structs.md#Vec3f) |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_dif(VEC_OUT Vec3f dest, Vec3f a, Vec3f b);`
