
## [shake_camera_handheld](#shake_camera_handheld)

### Description
Activates a handheld camera shake effect.
Calculates positional and focus adjustments to simulate manual movement

### Lua Example
`shake_camera_handheld(pos, focus)`

### Parameters
| Field | Type |
| ----- | ---- |
| pos | [Vec3f](structs.md#Vec3f) |
| focus | [Vec3f](structs.md#Vec3f) |

### Returns
- None

### C Prototype
`void shake_camera_handheld(Vec3f pos, VEC_OUT Vec3f focus);`
