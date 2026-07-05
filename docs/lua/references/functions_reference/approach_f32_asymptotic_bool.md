
## [approach_f32_asymptotic_bool](#approach_f32_asymptotic_bool)

### Description
Gradually adjusts a floating-point value (`current`) towards a target (`target`) using asymptotic smoothing.
Returns FALSE if `current` reaches the `target`

### Lua Example
`local integerValue, current = approach_f32_asymptotic_bool(current, target, multiplier)`

### Parameters
| Field | Type |
| ----- | ---- |
| current | `number` |
| target | `number` |
| multiplier | `number` |

### Returns
- `integer`
- `number`

### C Prototype
`s32 approach_f32_asymptotic_bool(INOUT f32 *current, f32 target, f32 multiplier);`
