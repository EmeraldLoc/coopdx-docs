
## [gfx_get_vertex_count](#gfx_get_vertex_count)

### Description
Gets the number of vertices from a display list command if it has the op `G_VTX`

### Lua Example
`local integerValue = gfx_get_vertex_count(cmd)`

### Parameters
| Field | Type |
| ----- | ---- |
| cmd | `Pointer` <`Gfx`> |

### Returns
- `integer`

### C Prototype
`u16 gfx_get_vertex_count(Gfx *cmd);`
