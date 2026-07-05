
## [slide_bonk](#slide_bonk)

### Description
Handles the scenario where Mario slides into a wall. If Mario is moving fast, reflects his velocity and transitions to a fast knockback, Otherwise, stops his forward velocity and sets a slower knockback

### Lua Example
`slide_bonk(m, fastAction, slowAction)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| fastAction | `integer` |
| slowAction | `integer` |

### Returns
- None

### C Prototype
`void slide_bonk(struct MarioState *m, u32 fastAction, u32 slowAction);`
