
## [vec3f_set](#vec3f_set)

### Description
Sets the values of the 3D floating-point vector `dest` to the given x, y, and z values

### Lua Example
`local vec3fValue = vec3f_set(dest, x, y, z)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| x | `number` |
| y | `number` |
| z | `number` |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_set(VEC_OUT Vec3f dest, f32 x, f32 y, f32 z);`
