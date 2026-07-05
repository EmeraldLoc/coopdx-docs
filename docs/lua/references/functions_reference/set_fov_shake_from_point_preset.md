
## [set_fov_shake_from_point_preset](#set_fov_shake_from_point_preset)

### Description
Applies a preset field-of-view shake effect relative to a specific point.
The intensity diminishes as the distance from the point increases

### Lua Example
`set_fov_shake_from_point_preset(preset, posX, posY, posZ)`

### Parameters
| Field | Type |
| ----- | ---- |
| preset | `integer` |
| posX | `number` |
| posY | `number` |
| posZ | `number` |

### Returns
- None

### C Prototype
`void set_fov_shake_from_point_preset(u8 preset, f32 posX, f32 posY, f32 posZ);`
