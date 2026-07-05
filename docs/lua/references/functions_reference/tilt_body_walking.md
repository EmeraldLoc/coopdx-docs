
## [tilt_body_walking](#tilt_body_walking)

### Description
Applies a left/right tilt to Mario's torso (and some pitch if running fast) while walking or running.
The tilt is based on his change in yaw and current speed, giving a leaning appearance when turning

### Lua Example
`tilt_body_walking(m, startYaw)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| startYaw | `integer` |

### Returns
- None

### C Prototype
`void tilt_body_walking(struct MarioState *m, s16 startYaw);`
