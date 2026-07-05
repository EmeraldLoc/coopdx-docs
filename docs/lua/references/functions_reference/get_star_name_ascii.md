
## [get_star_name_ascii](#get_star_name_ascii)

### Description
Returns the name of the star corresponding to `courseNum` and `starNum` as an ASCII (human readable) string.
Set `charCase` to 1 to capitalize or -1 to decapitalize the returned string

### Lua Example
`local stringValue = get_star_name_ascii(courseNum, starNum, charCase)`

### Parameters
| Field | Type |
| ----- | ---- |
| courseNum | `integer` |
| starNum | `integer` |
| charCase | `integer` |

### Returns
- `string`

### C Prototype
`const char *get_star_name_ascii(s16 courseNum, s16 starNum, s16 charCase);`
