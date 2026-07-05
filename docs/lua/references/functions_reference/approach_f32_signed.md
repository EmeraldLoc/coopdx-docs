
## [approach_f32_signed](#approach_f32_signed)

### Description
Approaches a value toward a target using signed increments. Returns `TRUE` when target is reached

### Lua Example
`local integerValue, value = approach_f32_signed(value, target, increment)`

### Parameters
| Field | Type |
| ----- | ---- |
| value | `number` |
| target | `number` |
| increment | `number` |

### Returns
- `integer`
- `number`

### C Prototype
`s32 approach_f32_signed(INOUT f32 *value, f32 target, f32 increment);`
