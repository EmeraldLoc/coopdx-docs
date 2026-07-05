
## [mario_get_terrain_sound_addend](#mario_get_terrain_sound_addend)

### Description
Computes a value added to terrain sounds, depending on the floor's type (sand, snow, water, etc.) and slipperiness. This returns a sound 'addend' used with sound effects.
Useful for playing context-specific footstep or movement sounds

### Lua Example
`local integerValue = mario_get_terrain_sound_addend(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`u32 mario_get_terrain_sound_addend(struct MarioState *m);`
