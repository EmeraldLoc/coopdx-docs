
## [mario_set_forward_vel](#mario_set_forward_vel)

### Description
Sets Mario's forward velocity (`m.forwardVel`) and updates `slideVelX/Z` and `m.vel` accordingly, based on `m.faceAngle.y`.
Useful for controlling Mario's speed and direction in various actions (jumping, walking, sliding, etc.)

### Lua Example
`mario_set_forward_vel(m, speed)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| speed | `number` |

### Returns
- None

### C Prototype
`void mario_set_forward_vel(struct MarioState *m, f32 speed);`
