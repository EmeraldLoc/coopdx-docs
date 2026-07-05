
## [play_sound_if_no_flag](#play_sound_if_no_flag)

### Description
Plays a sound if Mario does not currently have a specific flag set. Once played, the flag is set to prevent immediate repeats

### Lua Example
`play_sound_if_no_flag(m, soundBits, flags)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| soundBits | `integer` |
| flags | `integer` |

### Returns
- None

### C Prototype
`void play_sound_if_no_flag(struct MarioState *m, u32 soundBits, u32 flags);`
