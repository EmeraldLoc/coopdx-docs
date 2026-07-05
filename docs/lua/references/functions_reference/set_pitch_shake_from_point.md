
## [set_pitch_shake_from_point](#set_pitch_shake_from_point)

### Description
Applies a pitch shake effect to the camera, scaled by proximity to a specified point.
Simulates vibrations with intensity decreasing further from the point

### Lua Example
`set_pitch_shake_from_point(mag, decay, inc, maxDist, posX, posY, posZ)`

### Parameters
| Field | Type |
| ----- | ---- |
| mag | `integer` |
| decay | `integer` |
| inc | `integer` |
| maxDist | `number` |
| posX | `number` |
| posY | `number` |
| posZ | `number` |

### Returns
- None

### C Prototype
`void set_pitch_shake_from_point(s16 mag, s16 decay, s16 inc, f32 maxDist, f32 posX, f32 posY, f32 posZ);`
