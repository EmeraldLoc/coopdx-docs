
## [camera_approach_s16_symmetric_bool](#camera_approach_s16_symmetric_bool)

### Description
Adjusts a signed 16-bit integer (`current`) towards a target (`target`) symmetrically with a fixed increment (`increment`).
Returns FALSE if `current` reaches the `target`

### Lua Example
`local integerValue, current = camera_approach_s16_symmetric_bool(current, target, increment)`

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
`s32 camera_approach_s16_symmetric_bool(INOUT s16 *current, s16 target, s16 increment);`
