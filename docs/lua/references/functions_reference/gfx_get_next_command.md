
## [gfx_get_next_command](#gfx_get_next_command)

### Description
Gets the next command of a given display list pointer. Intended to use in a for loop

### Lua Example
`local pointerValue = gfx_get_next_command(gfx)`

### Parameters
| Field | Type |
| ----- | ---- |
| gfx | `Pointer` <`Gfx`> |

### Returns
- `Pointer` <`Gfx`>

### C Prototype
`Gfx *gfx_get_next_command(Gfx *gfx);`
