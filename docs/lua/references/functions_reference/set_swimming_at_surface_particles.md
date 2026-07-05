
## [set_swimming_at_surface_particles](#set_swimming_at_surface_particles)

### Description
Sets Mario's particle flags if he's at the surface of a water box

### Lua Example
`set_swimming_at_surface_particles(m, particleFlag)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| particleFlag | `integer` |

### Returns
- None

### C Prototype
`void set_swimming_at_surface_particles(struct MarioState *m, u32 particleFlag);`
