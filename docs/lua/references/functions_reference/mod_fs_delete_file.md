
## [mod_fs_delete_file](#mod_fs_delete_file)

### Description
Deletes the file at path `filepath` of the provided `modFs`. Returns true on success

### Lua Example
`local booleanValue = mod_fs_delete_file(modFs, filepath)`

### Parameters
| Field | Type |
| ----- | ---- |
| modFs | [ModFs](structs.md#ModFs) |
| filepath | `string` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_delete_file(struct ModFs *modFs, const char *filepath);`
