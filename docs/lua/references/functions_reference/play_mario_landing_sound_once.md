
## [play_mario_landing_sound_once](#play_mario_landing_sound_once)

### Description
A variant of `play_mario_landing_sound` that ensures the sound is only played once per action. Uses `play_mario_action_sound` internally

### Lua Example
`play_mario_landing_sound_once(m, soundBits)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| soundBits | `integer` |

### Returns
- None

### C Prototype
`void play_mario_landing_sound_once(struct MarioState *m, u32 soundBits);`
