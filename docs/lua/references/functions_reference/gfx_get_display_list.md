
## [gfx_get_display_list](#gfx_get_display_list)

### Description
Gets the display list from a display list command if it has the op `G_DL`

### Lua Example
`local pointerValue = gfx_get_display_list(cmd)`

### Parameters
| Field | Type |
| ----- | ---- |
| cmd | `Pointer` <`Gfx`> |

### Returns
- `Pointer` <`Gfx`>

### C Prototype
`Gfx *gfx_get_display_list(Gfx *cmd);`
