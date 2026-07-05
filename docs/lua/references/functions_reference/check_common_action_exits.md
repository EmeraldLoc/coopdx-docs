
## [check_common_action_exits](#check_common_action_exits)

### Description
Checks for inputs that cause common action transitions (jump, freefall, walking, sliding).
Useful for quickly exiting certain stationary actions when Mario begins moving or leaves the floor

### Lua Example
`local integerValue = check_common_action_exits(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 check_common_action_exits(struct MarioState *m);`
