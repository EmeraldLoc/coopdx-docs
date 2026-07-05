
## [mod_fs_file_read_bytes](#mod_fs_file_read_bytes)

### Description
Reads a bytestring of `length` bytes from a binary modfs `file`

### Lua Example
`local stringValue = mod_fs_file_read_bytes(file, length)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| length | `integer` |

### Returns
- `string`

### C Prototype
`ByteString mod_fs_file_read_bytes(struct ModFsFile *file, u32 length);`
