
## [gfx_get_command](#gfx_get_command)

### Description
Gets a command of a display list at position `offset`

### Lua Example
`local pointerValue = gfx_get_command(gfx, offset)`

### Parameters
| Field | Type |
| ----- | ---- |
| gfx | `Pointer` <`Gfx`> |
| offset | `integer` |

### Returns
- `Pointer` <`Gfx`>

### C Prototype
`Gfx *gfx_get_command(Gfx *gfx, u32 offset);`
