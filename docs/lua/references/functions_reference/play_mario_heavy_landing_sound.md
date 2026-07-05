
## [play_mario_heavy_landing_sound](#play_mario_heavy_landing_sound)

### Description
Plays a heavier, more forceful landing sound, possibly for ground pounds or large impacts. Takes into account whether Mario has a metal cap equipped.
Useful for making big impact landings stand out aurally

### Lua Example
`play_mario_heavy_landing_sound(m, soundBits)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| soundBits | `integer` |

### Returns
- None

### C Prototype
`void play_mario_heavy_landing_sound(struct MarioState *m, u32 soundBits);`
