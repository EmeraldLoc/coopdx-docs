
## [mod_fs_file_write_bool](#mod_fs_file_write_bool)

### Description
Writes a boolean to a binary modfs `file`. Returns true on success

### Lua Example
`local booleanValue = mod_fs_file_write_bool(file, value)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| value | `boolean` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_write_bool(struct ModFsFile *file, bool value);`
