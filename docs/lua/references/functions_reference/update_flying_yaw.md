
## [update_flying_yaw](#update_flying_yaw)

### Description
Calculates and applies a change in Mario's yaw while flying, based on horizontal stick input. Approaches a target yaw velocity
and sets Mario's roll angle to simulate banking turns. This results in a more natural, curved flight path

### Lua Example
`update_flying_yaw(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void update_flying_yaw(struct MarioState *m);`
