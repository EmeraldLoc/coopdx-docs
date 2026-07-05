
## [smlua_text_utils_act_name_mod_index](#smlua_text_utils_act_name_mod_index)

### Description
Gets the index of the mod that replaced the act name of `actNum` in `courseNum`

### Lua Example
`local integerValue = smlua_text_utils_act_name_mod_index(courseNum, actNum)`

### Parameters
| Field | Type |
| ----- | ---- |
| courseNum | `integer` |
| actNum | `integer` |

### Returns
- `integer`

### C Prototype
`s32 smlua_text_utils_act_name_mod_index(s16 courseNum, u8 actNum);`
