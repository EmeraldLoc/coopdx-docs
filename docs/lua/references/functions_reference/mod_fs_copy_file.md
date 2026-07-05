
## [mod_fs_copy_file](#mod_fs_copy_file)

### Description
Copies the file at path `srcpath` to `dstpath` of the provided `modFs`. Set `overwriteExisting` to true to overwrite the file at path `dstpath` if it exists. Returns true on success

### Lua Example
`local booleanValue = mod_fs_copy_file(modFs, srcpath, dstpath, overwriteExisting)`

### Parameters
| Field | Type |
| ----- | ---- |
| modFs | [ModFs](structs.md#ModFs) |
| srcpath | `string` |
| dstpath | `string` |
| overwriteExisting | `boolean` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_copy_file(struct ModFs *modFs, const char *srcpath, const char *dstpath, bool overwriteExisting);`
