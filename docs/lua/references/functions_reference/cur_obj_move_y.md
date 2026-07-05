
## [cur_obj_move_y](#cur_obj_move_y)

### Description
Moves the current object vertically while handling ground, water surface, and underwater states

### Lua Example
`cur_obj_move_y(gravity, bounciness, buoyancy)`

### Parameters
| Field | Type |
| ----- | ---- |
| gravity | `number` |
| bounciness | `number` |
| buoyancy | `number` |

### Returns
- None

### C Prototype
`void cur_obj_move_y(f32 gravity, f32 bounciness, f32 buoyancy);`
