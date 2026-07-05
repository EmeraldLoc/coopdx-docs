
## [set_camera_mode_fixed](#set_camera_mode_fixed)

### Description
Activates a fixed camera mode and aligns the camera to specific X, Y, Z coordinates.
This is useful for predefined static views in specific areas

### Lua Example
`local integerValue = set_camera_mode_fixed(c, x, y, z)`

### Parameters
| Field | Type |
| ----- | ---- |
| c | [Camera](structs.md#Camera) |
| x | `integer` |
| y | `integer` |
| z | `integer` |

### Returns
- `integer`

### C Prototype
`s32 set_camera_mode_fixed(struct Camera* c, s16 x, s16 y, s16 z);`
