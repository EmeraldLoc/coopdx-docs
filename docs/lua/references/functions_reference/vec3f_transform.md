
## [vec3f_transform](#vec3f_transform)

### Description
Scales the 3D floating-point vector `v` by the vector `scale`, then rotates it by the rotation vector `rotation`, and finally translates it by the vector `translation`. The resulting vector is stored in `dest`

### Lua Example
`local vec3fValue = vec3f_transform(dest, v, translation, rotation, scale)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| v | [Vec3f](structs.md#Vec3f) |
| translation | [Vec3f](structs.md#Vec3f) |
| rotation | [Vec3s](structs.md#Vec3s) |
| scale | [Vec3f](structs.md#Vec3f) |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_transform(VEC_OUT Vec3f dest, Vec3f v, Vec3f translation, Vec3s rotation, Vec3f scale);`
