
## [mod_fs_file_read_integer](#mod_fs_file_read_integer)

### Description
Reads an integer from a binary modfs `file`. `intType` must be one of the `INT_TYPE_*` constants

### Lua Example
`local integerValue = mod_fs_file_read_integer(file, intType)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| intType | [enum ModFsFileIntType](constants.md#enum-ModFsFileIntType) |

### Returns
- `integer`

### C Prototype
`lua_Integer mod_fs_file_read_integer(struct ModFsFile *file, enum ModFsFileIntType intType);`
