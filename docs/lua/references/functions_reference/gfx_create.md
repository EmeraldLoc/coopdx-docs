
## [gfx_create](#gfx_create)

### Description
Creates a new named display list of `length` commands

### Lua Example
`local pointerValue = gfx_create(name, length)`

### Parameters
| Field | Type |
| ----- | ---- |
| name | `string` |
| length | `integer` |

### Returns
- `Pointer` <`Gfx`>

### C Prototype
`Gfx *gfx_create(const char *name, u32 length);`
