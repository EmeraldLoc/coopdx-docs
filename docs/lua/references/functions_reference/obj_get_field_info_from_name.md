
## [obj_get_field_info_from_name](#obj_get_field_info_from_name)

### Description
Gets the object field info (index, sub-index and type) from a field name and a specific mod (if provided). Returns `true` if the field is found, `false` otherwise.
Supported types are `s32`, `u32`, `f32`, `s16`.
This function works with custom object fields as well and is meant to be used with functions that take a field index as parameter, like `obj_get_first_with_behavior_id_and_field_s32` or `obj_get_field_s32`

### Lua Example
`local booleanValue, fieldIndex, fieldSubIndex, fieldType = obj_get_field_info_from_name(fieldName, mod)`

### Parameters
| Field | Type |
| ----- | ---- |
| fieldName | `string` |
| mod | [Mod](structs.md#Mod) |

### Returns
- `boolean`
- `integer`
- `integer`
- `string`

### C Prototype
`bool obj_get_field_info_from_name(const char *fieldName, OPTIONAL struct Mod *mod, RET s32 *fieldIndex, RET s32 *fieldSubIndex, RET const char **fieldType);`
