
## [mod_fs_file_write_number](#mod_fs_file_write_number)

### Description
Writes an floating-point number to a binary modfs `file`. `floatType` must be one of the `FLOAT_TYPE_*` constants. Returns true on success

### Lua Example
`local booleanValue = mod_fs_file_write_number(file, value, floatType)`

### Parameters
| Field | Type |
| ----- | ---- |
| file | [ModFsFile](structs.md#ModFsFile) |
| value | `number` |
| floatType | [enum ModFsFileFloatType](constants.md#enum-ModFsFileFloatType) |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_file_write_number(struct ModFsFile *file, lua_Number value, enum ModFsFileFloatType floatType);`
