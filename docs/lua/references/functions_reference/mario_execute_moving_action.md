
## [mario_execute_moving_action](#mario_execute_moving_action)

### Description
Executes Mario's current moving actions by: checking common cancellations (e.g., water plunge, squish, death), handling quicksand updates, and switching to the correct sub-action handler based on `m.action`

### Lua Example
`local integerValue = mario_execute_moving_action(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 mario_execute_moving_action(struct MarioState *m);`
