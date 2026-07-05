
## [play_mario_sound](#play_mario_sound)

### Description
Plays a given action sound (like a jump or landing) and also a Mario voice line if certain conditions are met. It manages flags to avoid repeated sounds

### Lua Example
`play_mario_sound(m, primarySoundBits, scondarySoundBits)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| primarySoundBits | `integer` |
| scondarySoundBits | `integer` |

### Returns
- None

### C Prototype
`void play_mario_sound(struct MarioState *m, s32 primarySoundBits, s32 scondarySoundBits);`
