
## [play_step_sound](#play_step_sound)

### Description
Checks the current animation frame against two specified frames to trigger footstep sounds.
Also chooses specific sounds if Mario is wearing Metal Cap or is in quicksand

### Lua Example
`play_step_sound(m, frame1, frame2)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| frame1 | `integer` |
| frame2 | `integer` |

### Returns
- None

### C Prototype
`void play_step_sound(struct MarioState *m, s16 frame1, s16 frame2);`
