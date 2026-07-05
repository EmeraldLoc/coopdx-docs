
## [set_camera_mode](#set_camera_mode)

### Description
Changes the camera to a new mode, optionally interpolating over a specified number of frames.
Useful for transitioning between different camera behaviors dynamically

### Lua Example
`set_camera_mode(c, mode, frames)`

### Parameters
| Field | Type |
| ----- | ---- |
| c | [Camera](structs.md#Camera) |
| mode | `integer` |
| frames | `integer` |

### Returns
- None

### C Prototype
`void set_camera_mode(struct Camera *c, s16 mode, s16 frames);`
