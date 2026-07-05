
## [should_begin_sliding](#should_begin_sliding)

### Description
Checks if Mario should begin sliding, based on player input (facing downhill, pressing the analog stick backward, or on a slide terrain), and current floor steepness.
Returns true if conditions to slide are met.

### Lua Example
`local integerValue = should_begin_sliding(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 should_begin_sliding(struct MarioState *m);`
