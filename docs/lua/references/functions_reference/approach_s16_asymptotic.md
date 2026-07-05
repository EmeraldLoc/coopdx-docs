
## [approach_s16_asymptotic](#approach_s16_asymptotic)

### Description
Gradually approaches a signed 16-bit integer (`target`) using asymptotic smoothing.
The divisor controls the rate of the adjustment.
Useful for adjusting angles or positions smoothly

### Lua Example
`local integerValue = approach_s16_asymptotic(current, target, divisor)`

### Parameters
| Field | Type |
| ----- | ---- |
| current | `integer` |
| target | `integer` |
| divisor | `integer` |

### Returns
- `integer`

### C Prototype
`s32 approach_s16_asymptotic(s16 current, s16 target, s16 divisor);`
