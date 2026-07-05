
## [audio_stream_load](#audio_stream_load)

### Description
Loads an `audio` stream by `filename` (with extension)

### Lua Example
`local modAudioValue = audio_stream_load(filename)`

### Parameters
| Field | Type |
| ----- | ---- |
| filename | `string` |

### Returns
- [ModAudio](structs.md#ModAudio)

### C Prototype
`struct ModAudio* audio_stream_load(const char* filename);`
