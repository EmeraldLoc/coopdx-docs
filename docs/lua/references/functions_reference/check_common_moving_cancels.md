
## [check_common_moving_cancels](#check_common_moving_cancels)

### Description
Performs common checks when Mario is in a moving state, transitions to water plunge if underwater, handles squished or shockwave bounce scenarios, and checks for death conditions

### Lua Example
`local integerValue = check_common_moving_cancels(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 check_common_moving_cancels(struct MarioState *m);`
