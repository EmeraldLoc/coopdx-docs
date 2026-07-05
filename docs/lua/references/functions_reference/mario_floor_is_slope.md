
## [mario_floor_is_slope](#mario_floor_is_slope)

### Description
Checks whether Mario's floor is a slope, i.e., not flat but not necessarily steep. This depends on the floor's surface class and angle

### Lua Example
`local integerValue = mario_floor_is_slope(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 mario_floor_is_slope(struct MarioState *m);`
