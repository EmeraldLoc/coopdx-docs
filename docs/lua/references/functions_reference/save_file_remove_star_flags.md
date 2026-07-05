
## [save_file_remove_star_flags](#save_file_remove_star_flags)

### Description
Removes specific star flags from the save file. This modifies the bitmask representing collected stars for a course or castle secret stars.
Useful for undoing progress or debugging collected stars

### Lua Example
`save_file_remove_star_flags(fileIndex, courseIndex, starFlagsToRemove)`

### Parameters
| Field | Type |
| ----- | ---- |
| fileIndex | `integer` |
| courseIndex | `integer` |
| starFlagsToRemove | `integer` |

### Returns
- None

### C Prototype
`void save_file_remove_star_flags(s32 fileIndex, s32 courseIndex, u32 starFlagsToRemove);`
