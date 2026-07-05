
## [calc_new_obj_vel_and_pos_y](#calc_new_obj_vel_and_pos_y)

### Description
Updates an objects speed for gravity and updates Y position

### Lua Example
`calc_new_obj_vel_and_pos_y(objFloor, objFloorY, objVelX, objVelZ)`

### Parameters
| Field | Type |
| ----- | ---- |
| objFloor | [Surface](structs.md#Surface) |
| objFloorY | `number` |
| objVelX | `number` |
| objVelZ | `number` |

### Returns
- None

### C Prototype
`void calc_new_obj_vel_and_pos_y(struct Surface *objFloor, f32 objFloorY, f32 objVelX, f32 objVelZ);`
