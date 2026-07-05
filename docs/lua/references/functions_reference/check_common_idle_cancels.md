
## [check_common_idle_cancels](#check_common_idle_cancels)

### Description
Checks for and handles common conditions that would cancel Mario's current idle action.

### Lua Example
`local integerValue = check_common_idle_cancels(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 check_common_idle_cancels(struct MarioState *m);`
