
## [check_common_automatic_cancels](#check_common_automatic_cancels)

### Description
Checks if Mario should cancel his current automatic action, primarily by detecting if he falls into deep water. If so, transitions him to the water-plunge state

### Lua Example
`local integerValue = check_common_automatic_cancels(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 check_common_automatic_cancels(struct MarioState *m);`
