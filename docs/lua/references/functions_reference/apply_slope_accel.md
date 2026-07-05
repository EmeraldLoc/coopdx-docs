
## [apply_slope_accel](#apply_slope_accel)

### Description
Applies acceleration or deceleration based on the slope of the floor.
On downward slopes, Mario gains speed, while on upward slopes, Mario loses speed

### Lua Example
`apply_slope_accel(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void apply_slope_accel(struct MarioState *m);`
