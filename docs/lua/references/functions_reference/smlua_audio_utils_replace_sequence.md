
## [smlua_audio_utils_replace_sequence](#smlua_audio_utils_replace_sequence)

### Description
Replaces the sequence corresponding to `sequenceId` with one called `m64Name`.m64 with `bankId` and `defaultVolume`

### Lua Example
`smlua_audio_utils_replace_sequence(sequenceId, bankId, defaultVolume, m64Name)`

### Parameters
| Field | Type |
| ----- | ---- |
| sequenceId | `integer` |
| bankId | `integer` |
| defaultVolume | `integer` |
| m64Name | `string` |

### Returns
- None

### C Prototype
`void smlua_audio_utils_replace_sequence(u8 sequenceId, u8 bankId, u8 defaultVolume, const char* m64Name);`
