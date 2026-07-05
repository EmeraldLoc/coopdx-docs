
## [vec3i_set](#vec3i_set)

### Description
Sets the values of the 3D integer vector `dest` to the given x, y, and z values

### Lua Example
`local vec3iValue = vec3i_set(dest, x, y, z)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3i](structs.md#Vec3i) |
| x | `integer` |
| y | `integer` |
| z | `integer` |

### Returns
- [Vec3i](structs.md#Vec3i)

### C Prototype
`Vec3ip vec3i_set(VEC_OUT Vec3i dest, s32 x, s32 y, s32 z);`
