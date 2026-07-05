
## [check_common_hold_action_exits](#check_common_hold_action_exits)

### Description
Checks for inputs that cause common hold-action transitions (hold jump, hold freefall, hold walking, hold sliding)

### Lua Example
`local integerValue = check_common_hold_action_exits(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 check_common_hold_action_exits(struct MarioState *m);`
