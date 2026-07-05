
## [obj_roll_to_match_yaw_turn](#obj_roll_to_match_yaw_turn)

### Description
Rolls the current object to the move angle subtracted by `targetYaw`, clamping between negative and positive `maxRoll` and using `rollSpeed`

### Lua Example
`obj_roll_to_match_yaw_turn(targetYaw, maxRoll, rollSpeed)`

### Parameters
| Field | Type |
| ----- | ---- |
| targetYaw | `integer` |
| maxRoll | `integer` |
| rollSpeed | `integer` |

### Returns
- None

### C Prototype
`void obj_roll_to_match_yaw_turn(s16 targetYaw, s16 maxRoll, s16 rollSpeed);`
