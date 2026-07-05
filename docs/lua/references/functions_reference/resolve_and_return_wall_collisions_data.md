
## [resolve_and_return_wall_collisions_data](#resolve_and_return_wall_collisions_data)

### Description
Similar to `resolve_and_return_wall_collisions` but also returns detailed collision data (`WallCollisionData`). This can handle multiple walls and store them for further checks

### Lua Example
`resolve_and_return_wall_collisions_data(pos, offset, radius, collisionData)`

### Parameters
| Field | Type |
| ----- | ---- |
| pos | [Vec3f](structs.md#Vec3f) |
| offset | `number` |
| radius | `number` |
| collisionData | [WallCollisionData](structs.md#WallCollisionData) |

### Returns
- None

### C Prototype
`void resolve_and_return_wall_collisions_data(VEC_OUT Vec3f pos, f32 offset, f32 radius, struct WallCollisionData* collisionData);`
