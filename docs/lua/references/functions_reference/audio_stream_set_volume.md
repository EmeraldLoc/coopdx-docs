
## [audio_stream_set_volume](#audio_stream_set_volume)

### Description
Sets the volume of an `audio` stream

### Lua Example
`audio_stream_set_volume(audio, volume)`

### Parameters
| Field | Type |
| ----- | ---- |
| audio | [ModAudio](structs.md#ModAudio) |
| volume | `number` |

### Returns
- None

### C Prototype
`void audio_stream_set_volume(struct ModAudio* audio, f32 volume);`
