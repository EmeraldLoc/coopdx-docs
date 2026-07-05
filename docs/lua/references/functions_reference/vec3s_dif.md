
## [vec3s_dif](#vec3s_dif)

### Description
Subtracts the components of the 3D short integer vector `b` from the components of `a` and stores the result in `dest`

### Lua Example
`local vec3sValue = vec3s_dif(dest, a, b)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3s](structs.md#Vec3s) |
| a | [Vec3s](structs.md#Vec3s) |
| b | [Vec3s](structs.md#Vec3s) |

### Returns
- [Vec3s](structs.md#Vec3s)

### C Prototype
`Vec3sp vec3s_dif(VEC_OUT Vec3s dest, Vec3s a, Vec3s b);`
