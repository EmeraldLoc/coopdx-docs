
## [smlua_text_utils_act_name_replace](#smlua_text_utils_act_name_replace)

### Description
Replaces the act name of `actNum` in `courseNum` with `name`

### Lua Example
`smlua_text_utils_act_name_replace(courseNum, actNum, name)`

### Parameters
| Field | Type |
| ----- | ---- |
| courseNum | `integer` |
| actNum | `integer` |
| name | `string` |

### Returns
- None

### C Prototype
`void smlua_text_utils_act_name_replace(s16 courseNum, u8 actNum, const char* name);`
