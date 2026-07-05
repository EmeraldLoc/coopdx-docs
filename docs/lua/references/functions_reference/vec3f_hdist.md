
## [vec3f_hdist](#vec3f_hdist)

### Description
Calculates the horizontal distance between two 3D floating-point vectors `v1` and `v2`, as if their y component was 0

### Lua Example
`local numberValue = vec3f_hdist(v1, v2)`

### Parameters
| Field | Type |
| ----- | ---- |
| v1 | [Vec3f](structs.md#Vec3f) |
| v2 | [Vec3f](structs.md#Vec3f) |

### Returns
- `number`

### C Prototype
`f32 vec3f_hdist(Vec3f v1, Vec3f v2);`
