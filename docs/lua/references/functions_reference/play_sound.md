
## [play_sound](#play_sound)

### Description
Plays a sound (`soundBits`) at `pos` (usually `gGlobalSoundSource` or `m.header.gfx.cameraToObject`)

### Lua Example
`play_sound(soundBits, pos)`

### Parameters
| Field | Type |
| ----- | ---- |
| soundBits | `integer` |
| pos | [Vec3f](structs.md#Vec3f) |

### Returns
- None

### C Prototype
`void play_sound(s32 soundBits, f32 *pos);`
