
## [treat_far_home_as_mario](#treat_far_home_as_mario)

### Description
Treats far home as Mario. Returns the distance and angle to the nearest player

### Lua Example
`local distanceToPlayer, angleToPlayer = treat_far_home_as_mario(threshold)`

### Parameters
| Field | Type |
| ----- | ---- |
| threshold | `number` |

### Returns
- `integer`
- `integer`

### C Prototype
`void treat_far_home_as_mario(f32 threshold, RET s32* distanceToPlayer, RET s32* angleToPlayer);`
