
## [audio_stream_get_frequency](#audio_stream_get_frequency)

### Description
Gets the frequency of an `audio` stream

### Lua Example
`local numberValue = audio_stream_get_frequency(audio)`

### Parameters
| Field | Type |
| ----- | ---- |
| audio | [ModAudio](structs.md#ModAudio) |

### Returns
- `number`

### C Prototype
`f32 audio_stream_get_frequency(struct ModAudio* audio);`
