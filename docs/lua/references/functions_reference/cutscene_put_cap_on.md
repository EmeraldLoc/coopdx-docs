
## [cutscene_put_cap_on](#cutscene_put_cap_on)

### Description
Transitions Mario's state from having the cap in his hand to wearing it on his head. Clears the `MARIO_CAP_IN_HAND` flag, sets the `MARIO_CAP_ON_HEAD` flag, and plays the 'put cap on' sound

### Lua Example
`cutscene_put_cap_on(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void cutscene_put_cap_on(struct MarioState *m);`
