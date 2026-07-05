
## [mod_fs_file_read_number](#mod_fs_file_read_number)

### Description
Reads an floating-point number from a binary modfs `file`. `floatType` must be one of the `FLOAT_TYPE_*` constants

### Lua Example
`local numberValue = mod_fs_file_read_number(file, floatType)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| floatType | [enum ModFsFileFloatType](constants.md#enum-ModFsFileFloatType) |

### Returns
- `number`

### C Prototype
`lua_Number mod_fs_file_read_number(struct ModFsFile *file, enum ModFsFileFloatType floatType);`
