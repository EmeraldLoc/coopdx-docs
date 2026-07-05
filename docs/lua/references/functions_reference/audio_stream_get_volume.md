
## [audio_stream_get_volume](#audio_stream_get_volume)

### Description
Gets the volume of an `audio` stream

### Lua Example
`local numberValue = audio_stream_get_volume(audio)`

### Parameters
| Field | Type |
| ----- | ---- |
| audio | [ModAudio](structs.md#ModAudio) |

### Returns
- `number`

### C Prototype
`f32 audio_stream_get_volume(struct ModAudio* audio);`
