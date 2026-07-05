
## [set_or_approach_s16_symmetric](#set_or_approach_s16_symmetric)

### Description
Smoothly transitions or directly sets a signed 16-bit value (`current`) to approach a target (`target`).
Uses symmetric scaling for gradual or immediate adjustments.
Returns FALSE if `current` reaches the `target`

### Lua Example
`local integerValue, current = set_or_approach_s16_symmetric(current, target, increment)`

### Parameters
| Field | Type |
| ----- | ---- |
| current | `integer` |
| target | `integer` |
| increment | `integer` |

### Returns
- `integer`
- `integer`

### C Prototype
`s32 set_or_approach_s16_symmetric(INOUT s16 *current, s16 target, s16 increment);`
