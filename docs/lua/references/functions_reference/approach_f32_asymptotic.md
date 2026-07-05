
## [approach_f32_asymptotic](#approach_f32_asymptotic)

### Description
Gradually approaches a floating-point value (`target`) using asymptotic smoothing.
The rate of approach is controlled by the `multiplier`.
Useful for smoothly adjusting camera parameters like field-of-view or position

### Lua Example
`local numberValue = approach_f32_asymptotic(current, target, multiplier)`

### Parameters
| Field | Type |
| ----- | ---- |
| current | `number` |
| target | `number` |
| multiplier | `number` |

### Returns
- `number`

### C Prototype
`f32 approach_f32_asymptotic(f32 current, f32 target, f32 multiplier);`
