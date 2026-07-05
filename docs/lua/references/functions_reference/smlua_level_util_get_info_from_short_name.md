
## [smlua_level_util_get_info_from_short_name](#smlua_level_util_get_info_from_short_name)

### Description
Gets information on a custom level from `shortName`

### Lua Example
`local customLevelInfoValue = smlua_level_util_get_info_from_short_name(shortName)`

### Parameters
| Field | Type |
| ----- | ---- |
| shortName | `string` |

### Returns
- [CustomLevelInfo](structs.md#CustomLevelInfo)

### C Prototype
`struct CustomLevelInfo* smlua_level_util_get_info_from_short_name(const char* shortName);`
