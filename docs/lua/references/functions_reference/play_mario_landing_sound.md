
## [play_mario_landing_sound](#play_mario_landing_sound)

### Description
Plays a normal landing sound (or metal landing sound if Mario is metal) and spawns appropriate particle effects (water splash, dust, etc.)

### Lua Example
`play_mario_landing_sound(m, soundBits)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| soundBits | `integer` |

### Returns
- None

### C Prototype
`void play_mario_landing_sound(struct MarioState *m, u32 soundBits);`
