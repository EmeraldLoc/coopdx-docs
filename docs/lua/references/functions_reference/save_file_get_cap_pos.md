
## [save_file_get_cap_pos](#save_file_get_cap_pos)

### Description
Retrieves the current position of Mario's cap, if it is on the ground in the current level and area. The position is stored in the provided `capPos` parameter.
Useful for tracking the cap's location after it has been dropped or lost

### Lua Example
`local integerValue = save_file_get_cap_pos(capPos)`

### Parameters
| Field | Type |
| ----- | ---- |
| capPos | [Vec3s](structs.md#Vec3s) |

### Returns
- `integer`

### C Prototype
`s32 save_file_get_cap_pos(VEC_OUT Vec3s capPos);`
