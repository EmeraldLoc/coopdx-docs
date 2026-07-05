
## [offset_rotated](#offset_rotated)

### Description
Offsets a vector by rotating it in 3D space relative to a reference position.
This is useful for creating radial effects or dynamic transformations

### Lua Example
`offset_rotated(dst, from, to, rotation)`

### Parameters
| Field | Type |
| ----- | ---- |
| dst | [Vec3f](structs.md#Vec3f) |
| from | [Vec3f](structs.md#Vec3f) |
| to | [Vec3f](structs.md#Vec3f) |
| rotation | [Vec3s](structs.md#Vec3s) |

### Returns
- None

### C Prototype
`void offset_rotated(VEC_OUT Vec3f dst, Vec3f from, Vec3f to, Vec3s rotation);`
