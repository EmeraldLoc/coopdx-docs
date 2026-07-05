
## [save_file_set_flags](#save_file_set_flags)

### Description
Adds new flags to the save file's flag bitmask.
Useful for updating progress or triggering new gameplay features

### Lua Example
`save_file_set_flags(flags)`

### Parameters
| Field | Type |
| ----- | ---- |
| flags | `integer` |

### Returns
- None

### C Prototype
`void save_file_set_flags(u32 flags);`
