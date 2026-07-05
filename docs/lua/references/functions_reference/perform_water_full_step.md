
## [perform_water_full_step](#perform_water_full_step)

### Description
Performs a full water movement step where ceilings, floors, and walls are handled. Generally, you should use `perform_water_step` for the full step functionality

### Lua Example
`local integerValue = perform_water_full_step(m, nextPos)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| nextPos | [Vec3f](structs.md#Vec3f) |

### Returns
- `integer`

### C Prototype
`u32 perform_water_full_step(struct MarioState *m, VEC_OUT Vec3f nextPos);`
