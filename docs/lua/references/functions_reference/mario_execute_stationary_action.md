
## [mario_execute_stationary_action](#mario_execute_stationary_action)

### Description
Executes Mario's current object action by first checking common stationary cancels, then updating quicksand state.
Dispatches to the appropriate action function, such as idle, sleeping, crouching, ect

### Lua Example
`local integerValue = mario_execute_stationary_action(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 mario_execute_stationary_action(struct MarioState *m);`
