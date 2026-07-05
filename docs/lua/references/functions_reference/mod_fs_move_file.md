
## [mod_fs_move_file](#mod_fs_move_file)

### Description
Moves the file at path `oldpath` to `newpath` of the provided `modFs`. Set `overwriteExisting` to true to overwrite the file at path `newpath` if it exists. Returns true on success

### Lua Example
`local booleanValue = mod_fs_move_file(modFs, oldpath, newpath, overwriteExisting)`

### Parameters
| Field | Type |
| ----- | ---- |
| modFs | [ModFs](structs.md#ModFs) |
| oldpath | `string` |
| newpath | `string` |
| overwriteExisting | `boolean` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_move_file(struct ModFs *modFs, const char *oldpath, const char *newpath, bool overwriteExisting);`
