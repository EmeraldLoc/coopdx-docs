
## [mario_floor_is_steep](#mario_floor_is_steep)

### Description
Checks whether Mario's floor is steep enough to cause special behavior, such as forcing slides or preventing certain actions. Returns true if the slope is too steep.
Useful for restricting normal movement on surfaces with extreme angles

### Lua Example
`local integerValue = mario_floor_is_steep(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 mario_floor_is_steep(struct MarioState *m);`
