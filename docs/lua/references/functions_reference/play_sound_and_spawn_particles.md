
## [play_sound_and_spawn_particles](#play_sound_and_spawn_particles)

### Description
Plays the specified sound effect and spawns surface-appropriate particles (e.g., water splash, snow, sand). Checks if Mario is metal to adjust audio accordingly

### Lua Example
`play_sound_and_spawn_particles(m, soundBits, waveParticleType)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| soundBits | `integer` |
| waveParticleType | `integer` |

### Returns
- None

### C Prototype
`void play_sound_and_spawn_particles(struct MarioState *m, u32 soundBits, u32 waveParticleType);`
