
## [update_angle_from_move_flags](#update_angle_from_move_flags)

### Description
Computes and returns an angle depending on the current object's angle and move flags

### Lua Example
`local integerValue, angle = update_angle_from_move_flags(angle)`

### Parameters
| Field | Type |
| ----- | ---- |
| angle | `integer` |

### Returns
- `integer`
- `integer`

### C Prototype
`s32 update_angle_from_move_flags(INOUT s32 *angle);`
