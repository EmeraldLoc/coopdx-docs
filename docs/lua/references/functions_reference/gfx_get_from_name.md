
## [gfx_get_from_name](#gfx_get_from_name)

### Description
Gets a display list of the current mod from its name.
Returns a pointer to the display list and its length

### Lua Example
`local pointerValue, length = gfx_get_from_name(name)`

### Parameters
| Field | Type |
| ----- | ---- |
| name | `string` |

### Returns
- `Pointer` <`Gfx`>
- `integer`

### C Prototype
`Gfx *gfx_get_from_name(const char *name, RET u32 *length);`
