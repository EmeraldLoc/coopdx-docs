
## [mod_fs_file_read_line](#mod_fs_file_read_line)

### Description
Reads a line from a text modfs `file`

### Lua Example
`local stringValue = mod_fs_file_read_line(file)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |

### Returns
- `string`

### C Prototype
`const char *mod_fs_file_read_line(struct ModFsFile *file);`
