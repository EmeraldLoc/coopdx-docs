
## [mod_fs_file_write_string](#mod_fs_file_write_string)

### Description
Writes a string to a modfs `file`. Returns true on success

### Lua Example
`local booleanValue = mod_fs_file_write_string(file, str)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| str | `string` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_write_string(struct ModFsFile *file, const char *str);`
