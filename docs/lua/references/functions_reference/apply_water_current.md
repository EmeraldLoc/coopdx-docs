
## [apply_water_current](#apply_water_current)

### Description
Calculates a water current and outputs it in `step`

### Lua Example
`apply_water_current(m, step)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| step | [Vec3f](structs.md#Vec3f) |

### Returns
- None

### C Prototype
`void apply_water_current(struct MarioState *m, VEC_OUT Vec3f step);`
