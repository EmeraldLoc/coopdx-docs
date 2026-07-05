
## [cur_obj_rotate_yaw_toward](#cur_obj_rotate_yaw_toward)

### Description
Rotates the current object's yaw angle toward a target. Returns `TRUE` when target is reached

### Lua Example
`local integerValue = cur_obj_rotate_yaw_toward(target, increment)`

### Parameters
| Field | Type |
| ----- | ---- |
| target | `integer` |
| increment | `integer` |

### Returns
- `integer`

### C Prototype
`s32 cur_obj_rotate_yaw_toward(s16 target, s16 increment);`
