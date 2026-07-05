
## [cur_obj_detect_steep_floor](#cur_obj_detect_steep_floor)

### Description
Checks whether the object is moving into a steep floor or death plane and returns a collision code

### Lua Example
`local integerValue = cur_obj_detect_steep_floor(steepAngleDegrees)`

### Parameters
| Field | Type |
| ----- | ---- |
| steepAngleDegrees | `integer` |

### Returns
- `integer`

### C Prototype
`s32 cur_obj_detect_steep_floor(s16 steepAngleDegrees);`
