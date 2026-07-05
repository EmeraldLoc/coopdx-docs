
## [stop_sound](#stop_sound)

### Description
Stops a sound (`soundBits`) at `pos` (usually `gGlobalSoundSource` or `m.header.gfx.cameraToObject`)

### Lua Example
`stop_sound(soundBits, pos)`

### Parameters
| Field | Type |
| ----- | ---- |
| soundBits | `integer` |
| pos | [Vec3f](structs.md#Vec3f) |

### Returns
- None

### C Prototype
`void stop_sound(u32 soundBits, f32 *pos);`
