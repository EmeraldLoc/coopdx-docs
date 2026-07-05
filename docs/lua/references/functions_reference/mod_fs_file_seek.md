
## [mod_fs_file_seek](#mod_fs_file_seek)

### Description
Sets the current position of a modfs `file`.
If `origin` is `FILE_SEEK_SET`, file position is set to `offset`.
If `origin` is `FILE_SEEK_CUR`, `offset` is added to file current position.
If `origin` is `FILE_SEEK_END`, file position is set to `end of file + offset`.
Returns true on success

### Lua Example
`local booleanValue = mod_fs_file_seek(file, offset, origin)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| offset | `integer` |
| origin | [enum ModFsFileSeek](constants.md#enum-ModFsFileSeek) |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_seek(struct ModFsFile *file, s32 offset, enum ModFsFileSeek origin);`
