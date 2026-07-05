
## [save_file_get_flags](#save_file_get_flags)

### Description
Retrieves the bitmask of flags representing the current state of the save file. Flags indicate collected items, completed objectives, and other game states.
Useful for checking specific game progress details

### Lua Example
`local integerValue = save_file_get_flags()`

### Parameters
- None

### Returns
- `integer`

### C Prototype
`u32 save_file_get_flags(void);`
