
## [mario_execute_submerged_action](#mario_execute_submerged_action)

### Description
Executes Mario's current submerged action by first checking common submerged cancels, then setting quicksand depth and head angles to 0.
Dispatches to the appropriate action function, such as breaststroke, flutterkick, water punch, ect

### Lua Example
`local integerValue = mario_execute_submerged_action(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 mario_execute_submerged_action(struct MarioState *m);`
