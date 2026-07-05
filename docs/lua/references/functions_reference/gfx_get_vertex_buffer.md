
## [gfx_get_vertex_buffer](#gfx_get_vertex_buffer)

### Description
Gets the vertex buffer from a display list command if it has the op `G_VTX`

### Lua Example
`local pointerValue = gfx_get_vertex_buffer(cmd)`

### Parameters
| Field | Type |
| ----- | ---- |
| cmd | `Pointer` <`Gfx`> |

### Returns
- `Pointer` <`Vtx`>

### C Prototype
`Vtx *gfx_get_vertex_buffer(Gfx *cmd);`
