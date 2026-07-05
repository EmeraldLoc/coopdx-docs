
## [vec3i_div](#vec3i_div)

### Description
Divides each component of the 3D integer vector `dest` by the scalar value `a`

### Lua Example
`local vec3iValue = vec3i_div(dest, a)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3i](structs.md#Vec3i) |
| a | `number` |

### Returns
- [Vec3i](structs.md#Vec3i)

### C Prototype
`Vec3ip vec3i_div(VEC_OUT Vec3i dest, f32 a);`
