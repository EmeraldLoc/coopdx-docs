
## [vec3s_normalize](#vec3s_normalize)

### Description
Normalizes the 3D short integer vector `v` so that its length (magnitude) becomes 1, while retaining its direction

### Lua Example
`local vec3sValue = vec3s_normalize(v)`

### Parameters
| Field | Type |
| ----- | ---- |
| v | [Vec3s](structs.md#Vec3s) |

### Returns
- [Vec3s](structs.md#Vec3s)

### C Prototype
`Vec3sp vec3s_normalize(VEC_OUT Vec3s v);`
