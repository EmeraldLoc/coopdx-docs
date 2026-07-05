
## [level_register](#level_register)

### Description
Registers a fully custom level. Level ID begins at 50

### Lua Example
`local integerValue = level_register(scriptEntryName, courseNum, fullName, shortName, acousticReach, echoLevel1, echoLevel2, echoLevel3)`

### Parameters
| Field | Type |
| ----- | ---- |
| scriptEntryName | `string` |
| courseNum | `integer` |
| fullName | `string` |
| shortName | `string` |
| acousticReach | `integer` |
| echoLevel1 | `integer` |
| echoLevel2 | `integer` |
| echoLevel3 | `integer` |

### Returns
- `integer`

### C Prototype
`s16 level_register(const char* scriptEntryName, s16 courseNum, const char* fullName, const char* shortName, u32 acousticReach, u32 echoLevel1, u32 echoLevel2, u32 echoLevel3);`
