
## [check_wall_kick](#check_wall_kick)

### Description
Checks if Mario should wall kick after performing an air hit against a wall. If the input conditions (e.g., pressing A)
and the `wallKickTimer` allow, Mario transitions to `ACT_WALL_KICK_AIR`

### Lua Example
`local integerValue = check_wall_kick(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 check_wall_kick(struct MarioState *m);`
