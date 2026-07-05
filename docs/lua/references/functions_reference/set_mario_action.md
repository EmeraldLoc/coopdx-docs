
## [set_mario_action](#set_mario_action)

### Description
Sets Mario's action to the specified `action` and `actionArg`, routing through group-specific transition functions (e.g., airborne actions). Resets sound flags and updates internal timers

### Lua Example
`local integerValue = set_mario_action(m, action, actionArg)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| action | `integer` |
| actionArg | `integer` |

### Returns
- `integer`

### C Prototype
`u32 set_mario_action(struct MarioState *m, u32 action, u32 actionArg);`
