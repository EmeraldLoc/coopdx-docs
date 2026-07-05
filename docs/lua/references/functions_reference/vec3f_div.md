
## [vec3f_div](#vec3f_div)

### Description
Divides each component of the 3D floating-point vector `dest` by the scalar value `a`

### Lua Example
`local vec3fValue = vec3f_div(dest, a)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| a | `number` |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_div(VEC_OUT Vec3f dest, f32 a);`
