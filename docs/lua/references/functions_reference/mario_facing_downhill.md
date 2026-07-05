
## [mario_facing_downhill](#mario_facing_downhill)

### Description
Determines if Mario is facing downhill relative to his floor angle, optionally accounting for forward velocity direction. Returns true if he is oriented down the slope.
Useful for deciding if Mario will walk or slide on sloped floors

### Lua Example
`local integerValue = mario_facing_downhill(m, turnYaw)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| turnYaw | `integer` |

### Returns
- `integer`

### C Prototype
`s32 mario_facing_downhill(struct MarioState *m, s32 turnYaw);`
