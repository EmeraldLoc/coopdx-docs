
## [audio_stream_get_looping](#audio_stream_get_looping)

### Description
Gets if an `audio` stream is looping or not

### Lua Example
`local booleanValue = audio_stream_get_looping(audio)`

### Parameters
| Field | Type |
| ----- | ---- |
| audio | [ModAudio](structs.md#ModAudio) |

### Returns
- `boolean`

### C Prototype
`bool audio_stream_get_looping(struct ModAudio* audio);`
