
## [play_sound_with_freq_scale](#play_sound_with_freq_scale)

### Description
Plays a sound (`soundBits`) with `freqScale` at `pos` (usually `gGlobalSoundSource` or `m.header.gfx.cameraToObject`)

### Lua Example
`play_sound_with_freq_scale(soundBits, pos, freqScale)`

### Parameters
| Field | Type |
| ----- | ---- |
| soundBits | `integer` |
| pos | [Vec3f](structs.md#Vec3f) |
| freqScale | `number` |

### Returns
- None

### C Prototype
`void play_sound_with_freq_scale(s32 soundBits, f32* pos, f32 freqScale);`
