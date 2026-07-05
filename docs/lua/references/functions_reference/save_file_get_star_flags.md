
## [save_file_get_star_flags](#save_file_get_star_flags)

### Description
Retrieves the bitmask of stars collected in a specific course or castle secret stars (-1).
Useful for evaluating level progress and completion

### Lua Example
`local integerValue = save_file_get_star_flags(fileIndex, courseIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| fileIndex | `integer` |
| courseIndex | `integer` |

### Returns
- `integer`

### C Prototype
`u32 save_file_get_star_flags(s32 fileIndex, s32 courseIndex);`
