
## [audio_stream_get_volume_channel](#audio_stream_get_volume_channel)

### Description
Gets the volume channel of an `audio` stream

### Lua Example
`local integerValue = audio_stream_get_volume_channel(audio)`

### Parameters
| Field | Type |
| ----- | ---- |
| audio | [ModAudio](structs.md#ModAudio) |

### Returns
- `integer`

### C Prototype
`u8 audio_stream_get_volume_channel(struct ModAudio *audio);`
