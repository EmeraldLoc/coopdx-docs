
## [obj_check_if_facing_toward_angle](#obj_check_if_facing_toward_angle)

### Description
A series of checks using sin and cos to see if a given angle is facing in the same direction
of a given angle, within a certain range

### Lua Example
`local integerValue = obj_check_if_facing_toward_angle(base, goal, range)`

### Parameters
| Field | Type |
| ----- | ---- |
| base | `integer` |
| goal | `integer` |
| range | `integer` |

### Returns
- `integer`

### C Prototype
`s8 obj_check_if_facing_toward_angle(u32 base, u32 goal, s16 range);`
