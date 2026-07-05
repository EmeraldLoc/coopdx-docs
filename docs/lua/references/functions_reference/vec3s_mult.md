
## [vec3s_mult](#vec3s_mult)

### Description
Multiplies the components of the 3D short integer vector `dest` with the components of `a`

### Lua Example
`local vec3sValue = vec3s_mult(dest, a)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3s](structs.md#Vec3s) |
| a | [Vec3s](structs.md#Vec3s) |

### Returns
- [Vec3s](structs.md#Vec3s)

### C Prototype
`Vec3sp vec3s_mult(VEC_OUT Vec3s dest, Vec3s a);`
