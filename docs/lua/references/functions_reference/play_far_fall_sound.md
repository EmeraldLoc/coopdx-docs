
## [play_far_fall_sound](#play_far_fall_sound)

### Description
Plays a unique sound when Mario has fallen a significant distance without being invulnerable, twirling, or flying.
If the fall exceeds a threshold, triggers a "long fall" exclamation. Also sets a flag to prevent repeated triggering

### Lua Example
`play_far_fall_sound(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void play_far_fall_sound(struct MarioState *m);`
