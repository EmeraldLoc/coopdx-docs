
## [smlua_level_util_get_info_from_course_num](#smlua_level_util_get_info_from_course_num)

### Description
Gets information on a custom level from `courseNum`

### Lua Example
`local customLevelInfoValue = smlua_level_util_get_info_from_course_num(courseNum)`

### Parameters
| Field | Type |
| ----- | ---- |
| courseNum | `integer` |

### Returns
- [CustomLevelInfo](structs.md#CustomLevelInfo)

### C Prototype
`struct CustomLevelInfo* smlua_level_util_get_info_from_course_num(u8 courseNum);`
