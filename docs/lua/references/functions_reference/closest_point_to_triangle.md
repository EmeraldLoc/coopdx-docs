
## [closest_point_to_triangle](#closest_point_to_triangle)

### Description
Gets the closest point of the triangle to `src` and returns it in `out`.

### Lua Example
`closest_point_to_triangle(surf, src, out)`

### Parameters
| Field | Type |
| ----- | ---- |
| surf | [Surface](structs.md#Surface) |
| src | [Vec3f](structs.md#Vec3f) |
| out | [Vec3f](structs.md#Vec3f) |

### Returns
- None

### C Prototype
`void closest_point_to_triangle(struct Surface* surf, Vec3f src, VEC_OUT Vec3f out);`
