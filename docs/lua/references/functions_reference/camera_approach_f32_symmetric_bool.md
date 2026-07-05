
## [camera_approach_f32_symmetric_bool](#camera_approach_f32_symmetric_bool)

### Description
Adjusts a floating-point value (`current`) towards a target (`target`) symmetrically with a fixed increment (`increment`).
Returns FALSE if `current` reaches the `target`

### Lua Example
`local integerValue, current = camera_approach_f32_symmetric_bool(current, target, increment)`

### Parameters
| Field | Type |
| ----- | ---- |
| current | `number` |
| target | `number` |
| increment | `number` |

### Returns
- `integer`
- `number`

### C Prototype
`s32 camera_approach_f32_symmetric_bool(INOUT f32 *current, f32 target, f32 increment);`
