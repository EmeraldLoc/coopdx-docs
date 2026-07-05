
## [save_file_set_star_flags](#save_file_set_star_flags)

### Description
Adds specific star flags to the save file, indicating collected stars for a course or castle secret stars. Updates the save file flags as necessary.
Useful for recording progress after star collection

### Lua Example
`save_file_set_star_flags(fileIndex, courseIndex, starFlags)`

### Parameters
| Field | Type |
| ----- | ---- |
| fileIndex | `integer` |
| courseIndex | `integer` |
| starFlags | `integer` |

### Returns
- None

### C Prototype
`void save_file_set_star_flags(s32 fileIndex, s32 courseIndex, u32 starFlags);`
