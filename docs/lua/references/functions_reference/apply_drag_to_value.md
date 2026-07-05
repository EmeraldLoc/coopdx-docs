
## [apply_drag_to_value](#apply_drag_to_value)

### Description
Applies nonlinear drag to a value pointer based on drag strength

### Lua Example
`local value = apply_drag_to_value(value, dragStrength)`

### Parameters
| Field | Type |
| ----- | ---- |
| value | `number` |
| dragStrength | `number` |

### Returns
- `number`

### C Prototype
`void apply_drag_to_value(INOUT f32 *value, f32 dragStrength);`
