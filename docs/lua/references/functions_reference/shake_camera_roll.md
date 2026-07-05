
## [shake_camera_roll](#shake_camera_roll)

### Description
Applies a roll-based shake effect to the camera.
Simulates rotational disturbances caused by impacts or other events

### Lua Example
`local roll = shake_camera_roll(roll)`

### Parameters
| Field | Type |
| ----- | ---- |
| roll | `integer` |

### Returns
- `integer`

### C Prototype
`void shake_camera_roll(INOUT s16 *roll);`
