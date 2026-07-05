
## [update_air_without_turn](#update_air_without_turn)

### Description
Updates Mario's air movement without directly turning his facing angle to match his intended yaw. Instead, Mario can
move sideways relative to his current facing direction. Also checks horizontal wind and applies drag

### Lua Example
`update_air_without_turn(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void update_air_without_turn(struct MarioState *m);`
