
## [collide_with_walls](#collide_with_walls)

### Description
Checks for collisions between the camera and level geometry.
Adjusts the camera's position to avoid clipping into walls or obstacles

### Lua Example
`local integerValue = collide_with_walls(pos, offsetY, radius)`

### Parameters
| Field | Type |
| ----- | ---- |
| pos | [Vec3f](structs.md#Vec3f) |
| offsetY | `number` |
| radius | `number` |

### Returns
- `integer`

### C Prototype
`s32 collide_with_walls(VEC_OUT Vec3f pos, f32 offsetY, f32 radius);`
