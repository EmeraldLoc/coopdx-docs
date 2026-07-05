
## [get_star_name_sm64](#get_star_name_sm64)

### Description
Returns the name of the star corresponding to `courseNum` and `starNum` as an SM64 encoded string.
This function should not be used in Lua mods.
Set `charCase` to 1 to capitalize or -1 to decapitalize the returned string

### Lua Example
`local pointerValue = get_star_name_sm64(courseNum, starNum, charCase)`

### Parameters
| Field | Type |
| ----- | ---- |
| courseNum | `integer` |
| starNum | `integer` |
| charCase | `integer` |

### Returns
- `Pointer` <`integer`>

### C Prototype
`const u8 *get_star_name_sm64(s16 courseNum, s16 starNum, s16 charCase);`
