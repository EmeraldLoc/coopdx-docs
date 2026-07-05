
## [audio_sample_play](#audio_sample_play)

### Description
Plays an `audio` sample at `position` with `volume`

### Lua Example
`audio_sample_play(audio, position, volume)`

### Parameters
| Field | Type |
| ----- | ---- |
| audio | [ModAudio](structs.md#ModAudio) |
| position | [Vec3f](structs.md#Vec3f) |
| volume | `number` |

### Returns
- None

### C Prototype
`void audio_sample_play(struct ModAudio* audio, Vec3f position, f32 volume);`
