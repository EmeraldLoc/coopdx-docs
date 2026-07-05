
## [vec3f_mult](#vec3f_mult)

### Description
Multiplies the components of the 3D floating-point vector `dest` with the components of `a`

### Lua Example
`local vec3fValue = vec3f_mult(dest, a)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| a | [Vec3f](structs.md#Vec3f) |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_mult(VEC_OUT Vec3f dest, Vec3f a);`
