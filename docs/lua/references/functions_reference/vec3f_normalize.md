
## [vec3f_normalize](#vec3f_normalize)

### Description
Normalizes the 3D floating-point vector `v` so that its length (magnitude) becomes 1, while retaining its direction

### Lua Example
`local vec3fValue = vec3f_normalize(v)`

### Parameters
| Field | Type |
| ----- | ---- |
| v | [Vec3f](structs.md#Vec3f) |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_normalize(VEC_OUT Vec3f v);`
