
## [mod_fs_file_erase](#mod_fs_file_erase)

### Description
Erases `length` bytes or characters from a modfs `file`. Returns true on success

### Lua Example
`local booleanValue = mod_fs_file_erase(file, length)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| length | `integer` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_erase(struct ModFsFile *file, u32 length);`
