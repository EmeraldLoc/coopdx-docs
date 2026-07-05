
## [vec3i_normalize](#vec3i_normalize)

### Description
Normalizes the 3D integer vector `v` so that its length (magnitude) becomes 1, while retaining its direction

### Lua Example
`local vec3iValue = vec3i_normalize(v)`

### Parameters
| Field | Type |
| ----- | ---- |
| v | [Vec3i](structs.md#Vec3i) |

### Returns
- [Vec3i](structs.md#Vec3i)

### C Prototype
`Vec3ip vec3i_normalize(VEC_OUT Vec3i v);`
