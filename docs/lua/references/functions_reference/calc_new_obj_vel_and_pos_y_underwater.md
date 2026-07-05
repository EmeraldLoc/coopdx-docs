
## [calc_new_obj_vel_and_pos_y_underwater](#calc_new_obj_vel_and_pos_y_underwater)

### Description
Adjusts the current object's veloicty and y position for being underwater

### Lua Example
`calc_new_obj_vel_and_pos_y_underwater(objFloor, floorY, objVelX, objVelZ, waterY)`

### Parameters
| Field | Type |
| ----- | ---- |
| objFloor | [Surface](structs.md#Surface) |
| floorY | `number` |
| objVelX | `number` |
| objVelZ | `number` |
| waterY | `number` |

### Returns
- None

### C Prototype
`void calc_new_obj_vel_and_pos_y_underwater(struct Surface *objFloor, f32 floorY, f32 objVelX, f32 objVelZ, f32 waterY);`
