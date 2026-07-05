
## [play_mario_jump_sound](#play_mario_jump_sound)

### Description
Plays Mario's jump sound if it hasn't been played yet since the last action change. This helps avoid overlapping jump voice lines on repeated jumps

### Lua Example
`play_mario_jump_sound(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void play_mario_jump_sound(struct MarioState *m);`
