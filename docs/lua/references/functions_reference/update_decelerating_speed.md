
## [update_decelerating_speed](#update_decelerating_speed)

### Description
Gradually reduces Mario's forward speed to zero over time on level ground, unless otherwise influenced by slope or friction.
Returns true if Mario's speed reaches zero, meaning he has stopped

### Lua Example
`local integerValue = update_decelerating_speed(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 update_decelerating_speed(struct MarioState *m);`
