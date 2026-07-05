
## [audio_stream_play](#audio_stream_play)

### Description
Plays an `audio` stream with `volume`. `restart` sets the elapsed time back to 0.

### Lua Example
`audio_stream_play(audio, restart, volume)`

### Parameters
| Field | Type |
| ----- | ---- |
| audio | [ModAudio](structs.md#ModAudio) |
| restart | `boolean` |
| volume | `number` |

### Returns
- None

### C Prototype
`void audio_stream_play(struct ModAudio* audio, bool restart, f32 volume);`
