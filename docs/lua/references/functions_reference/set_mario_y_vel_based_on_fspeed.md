
## [set_mario_y_vel_based_on_fspeed](#set_mario_y_vel_based_on_fspeed)

### Description
Adjusts Mario's vertical velocity (`m.vel.y`) based on his forward speed. This function also accounts for conditions like quicksand to halve velocity

### Lua Example
`set_mario_y_vel_based_on_fspeed(m, initialVelY, multiplier)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| initialVelY | `number` |
| multiplier | `number` |

### Returns
- None

### C Prototype
`void set_mario_y_vel_based_on_fspeed(struct MarioState *m, f32 initialVelY, f32 multiplier);`
