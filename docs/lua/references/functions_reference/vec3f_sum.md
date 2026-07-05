
## [vec3f_sum](#vec3f_sum)

### Description
Adds the components of two 3D floating-point vectors `a` and `b` and stores the result in `dest`

### Lua Example
`local vec3fValue = vec3f_sum(dest, a, b)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| a | [Vec3f](structs.md#Vec3f) |
| b | [Vec3f](structs.md#Vec3f) |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_sum(VEC_OUT Vec3f dest, Vec3f a, Vec3f b);`
