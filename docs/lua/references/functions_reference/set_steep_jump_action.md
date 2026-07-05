
## [set_steep_jump_action](#set_steep_jump_action)

### Description
Transitions Mario into ACT_STEEP_JUMP if the floor is too steep, adjusting his forward velocity and orientation accordingly.
Useful for forcing special jump states on surfaces exceeding normal slope limits

### Lua Example
`set_steep_jump_action(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void set_steep_jump_action(struct MarioState *m);`
