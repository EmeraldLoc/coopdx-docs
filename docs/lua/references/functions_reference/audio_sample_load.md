
## [audio_sample_load](#audio_sample_load)

### Description
Loads an `audio` sample

### Lua Example
`local modAudioValue = audio_sample_load(filename)`

### Parameters
| Field | Type |
| ----- | ---- |
| filename | `string` |

### Returns
- [ModAudio](structs.md#ModAudio)

### C Prototype
`struct ModAudio* audio_sample_load(const char* filename);`
