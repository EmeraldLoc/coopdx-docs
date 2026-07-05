
## [play_knockback_sound](#play_knockback_sound)

### Description
Plays a knockback sound effect if Mario is hit or knocked back with significant velocity. The specific sound differs
depending on whether Mario's forward velocity is high enough to be considered a strong knockback

### Lua Example
`play_knockback_sound(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void play_knockback_sound(struct MarioState *m);`
