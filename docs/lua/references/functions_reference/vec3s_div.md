
## [vec3s_div](#vec3s_div)

### Description
Divides each component of the 3D short integer vector `dest` by the scalar value `a`

### Lua Example
`local vec3sValue = vec3s_div(dest, a)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3s](structs.md#Vec3s) |
| a | `number` |

### Returns
- [Vec3s](structs.md#Vec3s)

### C Prototype
`Vec3sp vec3s_div(VEC_OUT Vec3s dest, f32 a);`
