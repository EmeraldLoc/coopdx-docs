
## [get_level_name](#get_level_name)

### Description
Returns the name of the level corresponding to `courseNum`, `levelNum` and `areaIndex` as a decapitalized ASCII (human readable) string

### Lua Example
`local stringValue = get_level_name(courseNum, levelNum, areaIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| courseNum | `integer` |
| levelNum | `integer` |
| areaIndex | `integer` |

### Returns
- `string`

### C Prototype
`const char *get_level_name(s16 courseNum, s16 levelNum, s16 areaIndex);`
