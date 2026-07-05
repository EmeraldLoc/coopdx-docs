
## [save_file_reload](#save_file_reload)

### Description
Reloads the save file data into memory, optionally resetting all save files. Marks the save file as modified.
Useful for reloading state after data corruption or during development debugging

### Lua Example
`save_file_reload(load_all)`

### Parameters
| Field | Type |
| ----- | ---- |
| load_all | `integer` |

### Returns
- None

### C Prototype
`void save_file_reload(u8 load_all);`
