
## [mod_fs_get_file](#mod_fs_get_file)

### Description
Gets the file object at path `filepath` of the provided `modFs`. This function will return nil for a private modfs file, even if it exists

### Lua Example
`local modFsFileValue = mod_fs_get_file(modFs, filepath)`

### Parameters
| Field | Type |
| ----- | ---- |
| modFs | [ModFs](structs.md#ModFs) |
| filepath | `string` |

### Returns
- [ModFsFile](structs.md#ModFsFile)

### C Prototype
`struct ModFsFile *mod_fs_get_file(struct ModFs *modFs, const char *filepath);`
