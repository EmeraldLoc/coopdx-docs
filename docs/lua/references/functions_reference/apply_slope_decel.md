
## [apply_slope_decel](#apply_slope_decel)

### Description
Approaches Mario's forward velocity toward zero at a rate dependent on the floor's slipperiness.
This function can completely stop Mario if the slope is gentle enough or if friction is high

### Lua Example
`local integerValue = apply_slope_decel(m, decelCoef)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| decelCoef | `number` |

### Returns
- `integer`

### C Prototype
`s32 apply_slope_decel(struct MarioState *m, f32 decelCoef);`
