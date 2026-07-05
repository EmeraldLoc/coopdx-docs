
## [clear_move_flag](#clear_move_flag)

### Description
Clears the `flag` from the `bitSet`

### Lua Example
`local integerValue, bitSet = clear_move_flag(bitSet, flag)`

### Parameters
| Field | Type |
| ----- | ---- |
| bitSet | `integer` |
| flag | `integer` |

### Returns
- `integer`
- `integer`

### C Prototype
`s32 clear_move_flag(INOUT u32 *bitSet, s32 flag);`
