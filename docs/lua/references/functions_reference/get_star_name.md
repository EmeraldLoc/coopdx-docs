
## [get_star_name](#get_star_name)

### Description
Returns the name of the star corresponding to `courseNum` and `starNum` as a decapitalized ASCII (human readable) string

### Lua Example
`local stringValue = get_star_name(courseNum, starNum)`

### Parameters
| Field | Type |
| ----- | ---- |
| courseNum | `integer` |
| starNum | `integer` |

### Returns
- `string`

### C Prototype
`const char *get_star_name(s16 courseNum, s16 starNum);`
