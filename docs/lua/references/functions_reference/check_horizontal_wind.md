
## [check_horizontal_wind](#check_horizontal_wind)

### Description
Checks for the presence of a horizontal wind surface under Mario. If found, applies a push force to Mario's horizontal
velocity. Caps speed at certain thresholds, updates Mario's forward velocity and yaw for sliding/wind movement

### Lua Example
`local integerValue = check_horizontal_wind(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 check_horizontal_wind(struct MarioState *m);`
