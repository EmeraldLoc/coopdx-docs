
## [set_mario_particle_flags](#set_mario_particle_flags)

### Description
Sets Mario's particle flags to spawn various visual effects (dust, water splashes, etc.), with an option to clear or set new flags

### Lua Example
`set_mario_particle_flags(m, flags, clear)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| flags | `integer` |
| clear | `integer` |

### Returns
- None

### C Prototype
`void set_mario_particle_flags(struct MarioState* m, u32 flags, u8 clear);`
