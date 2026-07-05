
## [mario_is_ground_pound_landing](#mario_is_ground_pound_landing)

### Description
Returns true if Mario is in a ground pound landing state (`ACT_GROUND_POUND_LAND` or any ground action with `INT_GROUND_POUND` interaction)

### Lua Example
`local booleanValue = mario_is_ground_pound_landing(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `boolean`

### C Prototype
`bool mario_is_ground_pound_landing(struct MarioState *m);`
