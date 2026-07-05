
## [mod_fs_file_write_line](#mod_fs_file_write_line)

### Description
Writes a line to a text modfs `file`. Returns true on success

### Lua Example
`local booleanValue = mod_fs_file_write_line(file, str)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| str | `string` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_write_line(struct ModFsFile *file, const char *str);`
