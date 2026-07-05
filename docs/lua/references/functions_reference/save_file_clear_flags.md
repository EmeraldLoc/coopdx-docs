
## [save_file_clear_flags](#save_file_clear_flags)

### Description
Clears specific flags in the current save file. The flags are specified as a bitmask in the `flags` parameter. Ensures that the save file remains valid after clearing.
Useful for removing specific game states, such as collected items or completed objectives, without resetting the entire save

### Lua Example
`save_file_clear_flags(flags)`

### Parameters
| Field | Type |
| ----- | ---- |
| flags | `integer` |

### Returns
- None

### C Prototype
`void save_file_clear_flags(u32 flags);`
