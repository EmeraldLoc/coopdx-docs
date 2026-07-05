
## [vec3s_hdist](#vec3s_hdist)

### Description
Calculates the horizontal distance between two 3D short integer vectors `v1` and `v2`, as if their y component was 0

### Lua Example
`local numberValue = vec3s_hdist(v1, v2)`

### Parameters
| Field | Type |
| ----- | ---- |
| v1 | [Vec3s](structs.md#Vec3s) |
| v2 | [Vec3s](structs.md#Vec3s) |

### Returns
- `number`

### C Prototype
`f32 vec3s_hdist(Vec3s v1, Vec3s v2);`
