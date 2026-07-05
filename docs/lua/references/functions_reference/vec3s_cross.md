
## [vec3s_cross](#vec3s_cross)

### Description
Computes the cross product of two 3D short integer vectors `a` and `b` and stores the result in `dest`

### Lua Example
`local vec3sValue = vec3s_cross(dest, a, b)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3s](structs.md#Vec3s) |
| a | [Vec3s](structs.md#Vec3s) |
| b | [Vec3s](structs.md#Vec3s) |

### Returns
- [Vec3s](structs.md#Vec3s)

### C Prototype
`Vec3sp vec3s_cross(VEC_OUT Vec3s dest, Vec3s a, Vec3s b);`
