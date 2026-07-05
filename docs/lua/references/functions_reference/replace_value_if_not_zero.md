
## [replace_value_if_not_zero](#replace_value_if_not_zero)

### Description
Returns `replacement` if `replacement` is not zero. Otherwise, returns `value`

### Lua Example
`local numberValue = replace_value_if_not_zero(value, replacement)`

### Parameters
| Field | Type |
| ----- | ---- |
| value | `number` |
| replacement | `number` |

### Returns
- `number`

### C Prototype
`f32 replace_value_if_not_zero(f32 value, f32 replacement);`
