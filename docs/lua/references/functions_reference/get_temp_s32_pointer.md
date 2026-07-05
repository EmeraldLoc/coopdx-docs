
## [get_temp_s32_pointer](#get_temp_s32_pointer)

### Description
Returns a temporary signed 32-bit integer pointer with its value set to `initialValue`

### Lua Example
`local pointerValue = get_temp_s32_pointer(initialValue)`

### Parameters
| Field | Type |
| ----- | ---- |
| initialValue | `integer` |

### Returns
- `Pointer` <`integer`>

### C Prototype
`s32* get_temp_s32_pointer(s32 initialValue);`
