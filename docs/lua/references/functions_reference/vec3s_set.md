
## [vec3s_set](#vec3s_set)

### Description
Sets the values of the 3D short integer vector `dest` to the given x, y, and z values

### Lua Example
`local vec3sValue = vec3s_set(dest, x, y, z)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3s](structs.md#Vec3s) |
| x | `integer` |
| y | `integer` |
| z | `integer` |

### Returns
- [Vec3s](structs.md#Vec3s)

### C Prototype
`Vec3sp vec3s_set(VEC_OUT Vec3s dest, s16 x, s16 y, s16 z);`
