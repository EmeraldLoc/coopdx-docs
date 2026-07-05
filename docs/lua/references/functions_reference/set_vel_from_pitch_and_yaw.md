
## [set_vel_from_pitch_and_yaw](#set_vel_from_pitch_and_yaw)

### Description
Sets Mario's velocity to his forward velocity multiplied by the cosine and sine of his pitch and yaw

### Lua Example
`set_vel_from_pitch_and_yaw(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void set_vel_from_pitch_and_yaw(struct MarioState* m);`
