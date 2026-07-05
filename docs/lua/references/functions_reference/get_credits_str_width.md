
## [get_credits_str_width](#get_credits_str_width)

### Description
Calculates the pixel width of a given credits string. Each space is counted as 4 pixels, and any other character as 7 pixels. Stops counting at the null terminator

### Lua Example
`local integerValue = get_credits_str_width(str)`

### Parameters
| Field | Type |
| ----- | ---- |
| str | `Pointer` <`integer`> |

### Returns
- `integer`

### C Prototype
`s32 get_credits_str_width(char *str);`
