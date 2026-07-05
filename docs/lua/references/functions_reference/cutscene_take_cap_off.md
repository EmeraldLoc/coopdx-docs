
## [cutscene_take_cap_off](#cutscene_take_cap_off)

### Description
Transitions Mario's state from wearing the cap on his head to holding it in his hand. Clears the `MARIO_CAP_ON_HEAD` flag, sets the `MARIO_CAP_IN_HAND` flag, and plays the 'take cap off' sound

### Lua Example
`cutscene_take_cap_off(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void cutscene_take_cap_off(struct MarioState *m);`
