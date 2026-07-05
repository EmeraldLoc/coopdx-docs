
## [drop_and_set_mario_action](#drop_and_set_mario_action)

### Description
Drops any currently held object and sets Mario to a new action. This function is typically used when Mario transitions to states where he cannot hold objects

### Lua Example
`local integerValue = drop_and_set_mario_action(m, action, actionArg)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| action | `integer` |
| actionArg | `integer` |

### Returns
- `integer`

### C Prototype
`s32 drop_and_set_mario_action(struct MarioState *m, u32 action, u32 actionArg);`
