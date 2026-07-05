
## [find_floor_slope](#find_floor_slope)

### Description
Returns a slope angle based on comparing the floor heights slightly in front and behind Mario. It essentially calculates how steep the ground is in a specific yaw direction.
Useful for slope-based calculations such as setting walking or sliding behaviors

### Lua Example
`local integerValue = find_floor_slope(m, yawOffset)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| yawOffset | `integer` |

### Returns
- `integer`

### C Prototype
`s16 find_floor_slope(struct MarioState *m, s16 yawOffset);`
