
## [mario_execute_automatic_action](#mario_execute_automatic_action)

### Description
Executes Mario's current automatic action (e.g., climbing a pole, hanging, ledge-grabbing) by calling the corresponding function. It also checks for common cancellations, like falling into water.
Returns true if the action was canceled and a new action was set, or false otherwise

### Lua Example
`local integerValue = mario_execute_automatic_action(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 mario_execute_automatic_action(struct MarioState *m);`
