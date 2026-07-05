
## [audio_stream_set_loop_points](#audio_stream_set_loop_points)

### Description
Sets an `audio` stream's loop points in samples

### Lua Example
`audio_stream_set_loop_points(audio, loopStart, loopEnd)`

### Parameters
| Field | Type |
| ----- | ---- |
| audio | [ModAudio](structs.md#ModAudio) |
| loopStart | `integer` |
| loopEnd | `integer` |

### Returns
- None

### C Prototype
`void audio_stream_set_loop_points(struct ModAudio* audio, s64 loopStart, s64 loopEnd);`
