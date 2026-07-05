
## [mod_fs_file_read_bool](#mod_fs_file_read_bool)

### Description
Reads a boolean from a binary modfs `file`

### Lua Example
`local booleanValue = mod_fs_file_read_bool(file)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_read_bool(struct ModFsFile *file);`
