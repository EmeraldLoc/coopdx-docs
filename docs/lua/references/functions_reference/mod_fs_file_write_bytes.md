
## [mod_fs_file_write_bytes](#mod_fs_file_write_bytes)

### Description
Writes a bytestring to a modfs `file`. Returns true on success

### Lua Example
`local booleanValue = mod_fs_file_write_bytes(file, bytestring)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| bytestring | `string` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_write_bytes(struct ModFsFile *file, ByteString bytestring);`
