
## [mario_is_crouching](#mario_is_crouching)

### Description
Returns true if Mario is in any of the crouching or crawling states, checking his current action

### Lua Example
`local booleanValue = mario_is_crouching(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `boolean`

### C Prototype
`bool mario_is_crouching(struct MarioState *m);`
