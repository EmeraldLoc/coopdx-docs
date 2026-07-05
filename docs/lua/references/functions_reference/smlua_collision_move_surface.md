
## [smlua_collision_move_surface](#smlua_collision_move_surface)

### Description
Moves an existing collision surface to new vertex positions.
Recalculates the surface normal, origin offset, and Y bounds, removes the surface from its old spatial partition cells, and re-adds it to the correct cells.
The previous vertices are preserved for interpolation

### Lua Example
`smlua_collision_move_surface(surface, vertex1, vertex2, vertex3)`

### Parameters
| Field | Type |
| ----- | ---- |
| surface | [Surface](structs.md#Surface) |
| vertex1 | [Vec3s](structs.md#Vec3s) |
| vertex2 | [Vec3s](structs.md#Vec3s) |
| vertex3 | [Vec3s](structs.md#Vec3s) |

### Returns
- None

### C Prototype
`void smlua_collision_move_surface(struct Surface *surface, Vec3s vertex1, Vec3s vertex2, Vec3s vertex3);`
