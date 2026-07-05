
## [cur_obj_move_y_and_get_water_level](#cur_obj_move_y_and_get_water_level)

### Description
Applies gravity and buoyancy to vertical velocity and returns the water level at the current XZ position

### Lua Example
`local numberValue = cur_obj_move_y_and_get_water_level(gravity, buoyancy)`

### Parameters
| Field | Type |
| ----- | ---- |
| gravity | `number` |
| buoyancy | `number` |

### Returns
- `number`

### C Prototype
`f32 cur_obj_move_y_and_get_water_level(f32 gravity, f32 buoyancy);`
