
## [set_fov_shake](#set_fov_shake)

### Description
Applies a field-of-view shake effect to simulate zoom or focus disruptions.
Shake parameters, such as amplitude and decay, control the intensity

### Lua Example
`set_fov_shake(amplitude, decay, shakeSpeed)`

### Parameters
| Field | Type |
| ----- | ---- |
| amplitude | `integer` |
| decay | `integer` |
| shakeSpeed | `integer` |

### Returns
- None

### C Prototype
`void set_fov_shake(s16 amplitude, s16 decay, s16 shakeSpeed);`
