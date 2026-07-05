
## [adjust_sound_for_speed](#adjust_sound_for_speed)

### Description
Adjusts the pitch/volume of Mario's movement-based sounds according to his forward velocity (`m.forwardVel`).
Useful for adding dynamic audio feedback based on Mario's running or walking speed

### Lua Example
`adjust_sound_for_speed(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void adjust_sound_for_speed(struct MarioState *m);`
