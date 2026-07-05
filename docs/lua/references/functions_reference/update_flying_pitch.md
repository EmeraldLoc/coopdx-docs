
## [update_flying_pitch](#update_flying_pitch)

### Description
Calculates and applies a change in Mario's pitch while flying, based on vertical stick input. Approaches a target pitch velocity
and clamps the final pitch angle to a certain range, simulating a smooth flight control

### Lua Example
`update_flying_pitch(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void update_flying_pitch(struct MarioState *m);`
