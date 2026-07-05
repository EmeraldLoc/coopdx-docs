
## [smlua_text_utils_act_name_get](#smlua_text_utils_act_name_get)

### Description
Gets the act name of `actNum` in `courseNum`

### Lua Example
`local stringValue = smlua_text_utils_act_name_get(courseNum, actNum)`

### Parameters
| Field | Type |
| ----- | ---- |
| courseNum | `integer` |
| actNum | `integer` |

### Returns
- `string`

### C Prototype
`const char* smlua_text_utils_act_name_get(s16 courseNum, u8 actNum);`
