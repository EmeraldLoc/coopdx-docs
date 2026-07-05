
## [mod_fs_file_set_text_mode](#mod_fs_file_set_text_mode)

### Description
Marks the provided modfs `file` as text. Returns true on success

### Lua Example
`local booleanValue = mod_fs_file_set_text_mode(file, text)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| text | `boolean` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_set_text_mode(struct ModFsFile *file, bool text);`
