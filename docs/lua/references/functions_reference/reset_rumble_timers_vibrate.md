
## [reset_rumble_timers_vibrate](#reset_rumble_timers_vibrate)

### Description
Resets rumble timers and sets vibrate based on `level`

### Lua Example
`reset_rumble_timers_vibrate(m, level)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| level | `integer` |

### Returns
- None

### C Prototype
`void reset_rumble_timers_vibrate(struct MarioState* m, s32 level);`
