
## [scale_along_line](#scale_along_line)

### Description
Scales a point along a line between two 3D points (`from` and `to`).
The scaling factor determines how far along the line the resulting point will be.
The result is stored in the destination vector (`dest`)

### Lua Example
`scale_along_line(dest, from, to, scale)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| from | [Vec3f](structs.md#Vec3f) |
| to | [Vec3f](structs.md#Vec3f) |
| scale | `number` |

### Returns
- None

### C Prototype
`void scale_along_line(VEC_OUT Vec3f dest, Vec3f from, Vec3f to, f32 scale);`
