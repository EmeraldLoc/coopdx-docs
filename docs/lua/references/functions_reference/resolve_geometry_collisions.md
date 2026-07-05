
## [resolve_geometry_collisions](#resolve_geometry_collisions)

### Description
Resolves collisions between the camera and level geometry.
Adjusts the camera's position to prevent clipping or intersecting with objects

### Lua Example
`resolve_geometry_collisions(pos, lastGood)`

### Parameters
| Field | Type |
| ----- | ---- |
| pos | [Vec3f](structs.md#Vec3f) |
| lastGood | [Vec3f](structs.md#Vec3f) |

### Returns
- None

### C Prototype
`void resolve_geometry_collisions(VEC_OUT Vec3f pos, UNUSED Vec3f lastGood);`
