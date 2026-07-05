
## [play_mario_action_sound](#play_mario_action_sound)

### Description
Plays an action sound once per action, optionally spawning wave or dust particles depending on the surface. This sets the `MARIO_ACTION_SOUND_PLAYED` flag to prevent repeats

### Lua Example
`play_mario_action_sound(m, soundBits, waveParticleType)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| soundBits | `integer` |
| waveParticleType | `integer` |

### Returns
- None

### C Prototype
`void play_mario_action_sound(struct MarioState *m, u32 soundBits, u32 waveParticleType);`
