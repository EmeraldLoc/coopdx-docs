
## [mod_fs_file_read_string](#mod_fs_file_read_string)

### Description
Reads a string from a binary modfs `file`, or read the whole content of a text modfs `file`

### Lua Example
`local stringValue = mod_fs_file_read_string(file)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |

### Returns
- `string`

### C Prototype
`const char *mod_fs_file_read_string(struct ModFsFile *file);`
