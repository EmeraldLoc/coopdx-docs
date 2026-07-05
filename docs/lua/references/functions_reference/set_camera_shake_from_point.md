
## [set_camera_shake_from_point](#set_camera_shake_from_point)

### Description
Applies a shake effect to the camera, scaled by its proximity to a specified point.
The intensity decreases with distance from the point

### Lua Example
`set_camera_shake_from_point(shake, posX, posY, posZ)`

### Parameters
| Field | Type |
| ----- | ---- |
| shake | `integer` |
| posX | `number` |
| posY | `number` |
| posZ | `number` |

### Returns
- None

### C Prototype
`void set_camera_shake_from_point(s16 shake, f32 posX, f32 posY, f32 posZ);`
