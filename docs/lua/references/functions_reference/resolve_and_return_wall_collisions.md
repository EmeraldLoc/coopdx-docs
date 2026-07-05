
## [resolve_and_return_wall_collisions](#resolve_and_return_wall_collisions)

### Description
Checks for and resolves wall collisions at a given position `pos`, returning the last wall encountered. Primarily used to prevent Mario from going through walls.
Useful for collision detection when updating Mario's movement or adjusting his position

### Lua Example
`local surfaceValue = resolve_and_return_wall_collisions(pos, offset, radius)`

### Parameters
| Field | Type |
| ----- | ---- |
| pos | [Vec3f](structs.md#Vec3f) |
| offset | `number` |
| radius | `number` |

### Returns
- [Surface](structs.md#Surface)

### C Prototype
`struct Surface *resolve_and_return_wall_collisions(VEC_OUT Vec3f pos, f32 offset, f32 radius);`
