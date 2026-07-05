
## [get_level_name_ascii](#get_level_name_ascii)

### Description
Returns the name of the level corresponding to `courseNum`, `levelNum` and `areaIndex` as an ASCII (human readable) string.
Set `charCase` to 1 to capitalize or -1 to decapitalize the returned string

### Lua Example
`local stringValue = get_level_name_ascii(courseNum, levelNum, areaIndex, charCase)`

### Parameters
| Field | Type |
| ----- | ---- |
| courseNum | `integer` |
| levelNum | `integer` |
| areaIndex | `integer` |
| charCase | `integer` |

### Returns
- `string`

### C Prototype
`const char *get_level_name_ascii(s16 courseNum, s16 levelNum, s16 areaIndex, s16 charCase);`
