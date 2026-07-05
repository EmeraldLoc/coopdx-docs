
## [smlua_collision_add_surface](#smlua_collision_add_surface)

### Description
Allocates a new collision surface with the given vertices, computes the surface normal and other fields, and inserts it into the spatial partition.
Returns the new surface, or `nil` if the triangle is degenerate (zero area).
Set `dynamic` to `true` for surfaces that are cleared each frame, or `false` for persistent static surfaces

### Lua Example
`local surfaceValue = smlua_collision_add_surface(dynamic, surfaceType, vertex1, vertex2, vertex3)`

### Parameters
| Field | Type |
| ----- | ---- |
| dynamic | `boolean` |
| surfaceType | `integer` |
| vertex1 | [Vec3s](structs.md#Vec3s) |
| vertex2 | [Vec3s](structs.md#Vec3s) |
| vertex3 | [Vec3s](structs.md#Vec3s) |

### Returns
- [Surface](structs.md#Surface)

### C Prototype
`struct Surface* smlua_collision_add_surface(bool dynamic, s16 surfaceType, Vec3s vertex1, Vec3s vertex2, Vec3s vertex3);`
