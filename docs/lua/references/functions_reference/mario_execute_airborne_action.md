
## [mario_execute_airborne_action](#mario_execute_airborne_action)

### Description
Executes Mario's current airborne action by first checking common airborne cancels, then playing a far-fall sound if needed.
Dispatches to the appropriate action function, such as jump, double jump, freefall, etc

### Lua Example
`local integerValue = mario_execute_airborne_action(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 mario_execute_airborne_action(struct MarioState *m);`
