
## [audio_stream_set_volume_channel](#audio_stream_set_volume_channel)

### Description
Sets the volume channel of an `audio` stream

### Lua Example
`audio_stream_set_volume_channel(audio, channel)`

### Parameters
| Field | Type |
| ----- | ---- |
| audio | [ModAudio](structs.md#ModAudio) |
| channel | `integer` |

### Returns
- None

### C Prototype
`void audio_stream_set_volume_channel(struct ModAudio *audio, u8 channel);`
