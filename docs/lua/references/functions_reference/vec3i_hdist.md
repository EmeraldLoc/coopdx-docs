
## [vec3i_hdist](#vec3i_hdist)

### Description
Calculates the horizontal distance between two 3D integer vectors `v1` and `v2`, as if their y component was 0

### Lua Example
`local numberValue = vec3i_hdist(v1, v2)`

### Parameters
| Field | Type |
| ----- | ---- |
| v1 | [Vec3i](structs.md#Vec3i) |
| v2 | [Vec3i](structs.md#Vec3i) |

### Returns
- `number`

### C Prototype
`f32 vec3i_hdist(Vec3i v1, Vec3i v2);`
