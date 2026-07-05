
## [mod_fs_file_write_integer](#mod_fs_file_write_integer)

### Description
Writes an integer to a binary modfs `file`. `intType` must be one of the `INT_TYPE_*` constants. Returns true on success

### Lua Example
`local booleanValue = mod_fs_file_write_integer(file, value, intType)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| value | `integer` |
| intType | [enum ModFsFileIntType](constants.md#enum-ModFsFileIntType) |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_write_integer(struct ModFsFile *file, lua_Integer value, enum ModFsFileIntType intType);`
