
## [vec3f_project](#vec3f_project)

### Description
Projects the 3D floating-point vector `v` onto another 3D floating-point vector `onto`. The resulting projection, stored in `dest`, represents how much of `v` lies along the direction of `onto`

### Lua Example
`local vec3fValue = vec3f_project(dest, v, onto)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| v | [Vec3f](structs.md#Vec3f) |
| onto | [Vec3f](structs.md#Vec3f) |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_project(VEC_OUT Vec3f dest, Vec3f v, Vec3f onto);`
