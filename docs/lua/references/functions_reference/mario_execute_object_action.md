
## [mario_execute_object_action](#mario_execute_object_action)

### Description
Executes Mario's current object action by first checking common object cancels, then updating quicksand state.
Dispatches to the appropriate action function, such as punching, throwing, picking up Bowser, etc

### Lua Example
`local integerValue = mario_execute_object_action(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 mario_execute_object_action(struct MarioState *m);`
