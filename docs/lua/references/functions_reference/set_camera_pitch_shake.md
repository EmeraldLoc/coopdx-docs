
## [set_camera_pitch_shake](#set_camera_pitch_shake)

### Description
Applies a pitch-based shake effect to the camera.
The shake's magnitude, decay, and increment are configurable.
Simulates vertical disturbances like impacts or explosions

### Lua Example
`set_camera_pitch_shake(mag, decay, inc)`

### Parameters
| Field | Type |
| ----- | ---- |
| mag | `integer` |
| decay | `integer` |
| inc | `integer` |

### Returns
- None

### C Prototype
`void set_camera_pitch_shake(s16 mag, s16 decay, s16 inc);`
