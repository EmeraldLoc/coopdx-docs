
## [vec3f_mul](#vec3f_mul)

### Description
Multiplies each component of the 3D floating-point vector `dest` by the scalar value `a`

### Lua Example
`local vec3fValue = vec3f_mul(dest, a)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| a | `number` |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_mul(VEC_OUT Vec3f dest, f32 a);`
