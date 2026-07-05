
## [check_kick_or_dive_in_air](#check_kick_or_dive_in_air)

### Description
Checks if Mario should perform a kick or a dive while in mid-air, depending on his current forward velocity.
Pressing the B button in the air can trigger a jump kick (at lower speeds) or a dive (at higher speeds)

### Lua Example
`local integerValue = check_kick_or_dive_in_air(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 check_kick_or_dive_in_air(struct MarioState *m);`
