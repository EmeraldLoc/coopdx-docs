
## [find_vector_perpendicular_to_plane](#find_vector_perpendicular_to_plane)

### Description
Determines a vector that is perpendicular (normal) to the plane defined by three given 3D floating-point points `a`, `b`, and `c`. The resulting perpendicular vector is stored in `dest`

### Lua Example
`local vec3fValue = find_vector_perpendicular_to_plane(dest, a, b, c)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| a | [Vec3f](structs.md#Vec3f) |
| b | [Vec3f](structs.md#Vec3f) |
| c | [Vec3f](structs.md#Vec3f) |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp find_vector_perpendicular_to_plane(VEC_OUT Vec3f dest, Vec3f a, Vec3f b, Vec3f c);`
