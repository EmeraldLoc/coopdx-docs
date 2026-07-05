
## [get_level_name_sm64](#get_level_name_sm64)

### Description
Returns the name of the level corresponding to `courseNum`, `levelNum` and `areaIndex` as an SM64 encoded string.
This function should not be used in Lua mods.
Set `charCase` to 1 to capitalize or -1 to decapitalize the returned string

### Lua Example
`local pointerValue = get_level_name_sm64(courseNum, levelNum, areaIndex, charCase)`

### Parameters
| Field | Type |
| ----- | ---- |
| courseNum | `integer` |
| levelNum | `integer` |
| areaIndex | `integer` |
| charCase | `integer` |

### Returns
- `Pointer` <`integer`>

### C Prototype
`const u8 *get_level_name_sm64(s16 courseNum, s16 levelNum, s16 areaIndex, s16 charCase);`
