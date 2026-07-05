
## [le_get_light_color](#le_get_light_color)

### Description
Outputs a lighting engine point light's color to `out`

### Lua Example
`le_get_light_color(id, out)`

### Parameters
| Field | Type |
| ----- | ---- |
| id | `integer` |
| out | [Color](structs.md#Color) |

### Returns
- None

### C Prototype
`void le_get_light_color(s16 id, VEC_OUT Color out);`
