
## [smlua_collision_delete_surface](#smlua_collision_delete_surface)

### Description
Fully deletes a collision surface: removes it from the spatial partitions and frees its pool slot.

### Lua Example
`smlua_collision_delete_surface(surface)`

### Parameters
| Field | Type |
| ----- | ---- |
| surface | [Surface](structs.md#Surface) |

### Returns
- None

### C Prototype
`void smlua_collision_delete_surface(struct Surface *surface);`
