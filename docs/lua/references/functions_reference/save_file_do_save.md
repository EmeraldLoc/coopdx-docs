
## [save_file_do_save](#save_file_do_save)

### Description
Saves the current state of the game into a specified save file. Includes data verification and backup management.
Useful for maintaining game progress during play or when saving manually

### Lua Example
`save_file_do_save(fileIndex, forceSave)`

### Parameters
| Field | Type |
| ----- | ---- |
| fileIndex | `integer` |
| forceSave | `integer` |

### Returns
- None

### C Prototype
`void save_file_do_save(s32 fileIndex, s8 forceSave);`
