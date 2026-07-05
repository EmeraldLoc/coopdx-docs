
## [smlua_level_util_get_info](#smlua_level_util_get_info)

### Description
Gets information on a custom level from `levelNum`

### Lua Example
`local customLevelInfoValue = smlua_level_util_get_info(levelNum)`

### Parameters
| Field | Type |
| ----- | ---- |
| levelNum | `integer` |

### Returns
- [CustomLevelInfo](structs.md#CustomLevelInfo)

### C Prototype
`struct CustomLevelInfo* smlua_level_util_get_info(s16 levelNum);`
