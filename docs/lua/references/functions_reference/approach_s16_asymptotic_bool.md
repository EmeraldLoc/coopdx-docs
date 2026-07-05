
## [approach_s16_asymptotic_bool](#approach_s16_asymptotic_bool)

### Description
Gradually adjusts a signed 16-bit integer (`current`) towards a target (`target`) using asymptotic smoothing.
Returns FALSE if `current` reaches `target`

### Lua Example
`local integerValue, current = approach_s16_asymptotic_bool(current, target, divisor)`

### Parameters
| Field | Type |
| ----- | ---- |
| current | `integer` |
| target | `integer` |
| divisor | `integer` |

### Returns
- `integer`
- `integer`

### C Prototype
`s32 approach_s16_asymptotic_bool(INOUT s16 *current, s16 target, s16 divisor);`
