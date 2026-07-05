
## [mod_fs_file_is_eof](#mod_fs_file_is_eof)

### Description
Returns true if the provided modfs `file` has reached its end of file

### Lua Example
`local booleanValue = mod_fs_file_is_eof(file)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_is_eof(struct ModFsFile *file);`
