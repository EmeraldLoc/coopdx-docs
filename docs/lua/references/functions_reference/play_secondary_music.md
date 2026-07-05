
## [play_secondary_music](#play_secondary_music)

### Description
Plays fading in secondary music `seqId` at `volume` over `fadeTimer` and sets the current background music's volume to `bgMusicVolume`

### Lua Example
`play_secondary_music(seqId, bgMusicVolume, volume, fadeTimer)`

### Parameters
| Field | Type |
| ----- | ---- |
| seqId | `integer` |
| bgMusicVolume | `integer` |
| volume | `integer` |
| fadeTimer | `integer` |

### Returns
- None

### C Prototype
`void play_secondary_music(u8 seqId, u8 bgMusicVolume, u8 volume, u16 fadeTimer);`
