
## [gfx_get_texture](#gfx_get_texture)

### Description
Gets the texture from a display list command if it has an image related op

### Lua Example
`local pointerValue = gfx_get_texture(cmd)`

### Parameters
| Field | Type |
| ----- | ---- |
| cmd | `Pointer` <`Gfx`> |

### Returns
- `Pointer` <`Texture`>

### C Prototype
`Texture *gfx_get_texture(Gfx *cmd);`
