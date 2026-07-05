
## [mod_fs_file_fill](#mod_fs_file_fill)

### Description
Fills a modfs `file` with `byte` repeated `length` times. Returns true on success

### Lua Example
`local booleanValue = mod_fs_file_fill(file, byte, length)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| byte | `integer` |
| length | `integer` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_fill(struct ModFsFile *file, u8 byte, u32 length);`
