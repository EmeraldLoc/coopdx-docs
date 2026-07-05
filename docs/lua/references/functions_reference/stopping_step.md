
## [stopping_step](#stopping_step)

### Description
Runs a stationary step, sets the character animation, and changes action if the animation has ended

### Lua Example
`stopping_step(m, animID, action)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| animID | `integer` |
| action | `integer` |

### Returns
- None

### C Prototype
`void stopping_step(struct MarioState *m, s32 animID, u32 action);`
