
## [landing_step](#landing_step)

### Description
Runs a stationary step, sets the character animation, and changes action if the animation has ended

### Lua Example
`local integerValue = landing_step(m, animID, action)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| animID | `integer` |
| action | `integer` |

### Returns
- `integer`

### C Prototype
`s32 landing_step(struct MarioState *m, s32 animID, u32 action);`
