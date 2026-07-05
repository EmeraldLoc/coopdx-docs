
## [cur_obj_scale_over_time](#cur_obj_scale_over_time)

### Description
Smoothly scales between `minScale` and `maxScale` the current object over a `duration` using enabled `axes` (1 = x, 2 = y, 4 = z, can be combined)

### Lua Example
`cur_obj_scale_over_time(axes, duration, minScale, maxScale)`

### Parameters
| Field | Type |
| ----- | ---- |
| axes | `integer` |
| duration | `integer` |
| minScale | `number` |
| maxScale | `number` |

### Returns
- None

### C Prototype
`void cur_obj_scale_over_time(s32 axes, s32 duration, f32 minScale, f32 maxScale);`
