
## [mod_fs_file_set_compression](#mod_fs_file_set_compression)

### Description
Sets the compression level of the provided modfs `file`. Must be between 0 (no compression) and 9 (most compression). Returns true on success.

### Lua Example
`local booleanValue = mod_fs_file_set_compression(file, level)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| level | `integer` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_set_compression(struct ModFsFile *file, s32 level);`
