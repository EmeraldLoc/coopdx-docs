
## [vec3f_rotate_around_n](#vec3f_rotate_around_n)

### Description
Rotates the 3D floating-point vector `v` around the vector `n`, given a rotation `r` (in sm64 angle units), and stores the result in `dest`

### Lua Example
`local vec3fValue = vec3f_rotate_around_n(dest, v, n, r)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| v | [Vec3f](structs.md#Vec3f) |
| n | [Vec3f](structs.md#Vec3f) |
| r | `integer` |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_rotate_around_n(VEC_OUT Vec3f dest, Vec3f v, Vec3f n, s16 r);`
