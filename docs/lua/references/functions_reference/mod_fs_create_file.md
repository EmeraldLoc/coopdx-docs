
## [mod_fs_create_file](#mod_fs_create_file)

### Description
Creates a new file at path `filepath` for the provided `modFs`. Set `text` to true to treat the file as a pure text file, not a binary file. Returns the created file on success

### Lua Example
`local modFsFileValue = mod_fs_create_file(modFs, filepath, text)`

### Parameters
| Field | Type |
| ----- | ---- |
| modFs | [ModFs](structs.md#ModFs) |
| filepath | `string` |
| text | `boolean` |

### Returns
- [ModFsFile](structs.md#ModFsFile)

### C Prototype
`struct ModFsFile *mod_fs_create_file(struct ModFs *modFs, const char *filepath, bool text);`
