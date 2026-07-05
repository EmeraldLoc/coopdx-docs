
## [mod_fs_file_set_public](#mod_fs_file_set_public)

### Description
Marks the provided modfs `file` as public (i.e. readable by other mods). Returns true on success

### Lua Example
`local booleanValue = mod_fs_file_set_public(file, pub)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| pub | `boolean` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_set_public(struct ModFsFile *file, bool pub);`
