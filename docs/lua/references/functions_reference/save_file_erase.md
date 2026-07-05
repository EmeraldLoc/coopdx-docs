
## [save_file_erase](#save_file_erase)

### Description
Erases all data in a specified save file, including backup slots. Marks the save file as modified and performs a save to apply the changes.
Useful for resetting a save file to its default state

### Lua Example
`save_file_erase(fileIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| fileIndex | `integer` |

### Returns
- None

### C Prototype
`void save_file_erase(s32 fileIndex);`
