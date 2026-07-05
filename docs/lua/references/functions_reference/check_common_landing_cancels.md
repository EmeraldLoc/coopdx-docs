
## [check_common_landing_cancels](#check_common_landing_cancels)

### Description
Checks for and handles common conditions that would cancel Mario's current landing action.

### Lua Example
`local integerValue = check_common_landing_cancels(m, action)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| action | `integer` |

### Returns
- `integer`

### C Prototype
`s32 check_common_landing_cancels(struct MarioState *m, u32 action);`
