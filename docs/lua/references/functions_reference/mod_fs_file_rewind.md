
## [mod_fs_file_rewind](#mod_fs_file_rewind)

### Description
Sets the current position of a modfs `file` to its beginning.
Returns true on success

### Lua Example
`local booleanValue = mod_fs_file_rewind(file)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_rewind(struct ModFsFile *file);`
