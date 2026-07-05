
## [vtx_get_vertex](#vtx_get_vertex)

### Description
Gets a vertex of a vertex buffer at position `offset`

### Lua Example
`local pointerValue = vtx_get_vertex(vtx, offset)`

### Parameters
| Field | Type |
| ----- | ---- |
| vtx | `Pointer` <`Vtx`> |
| offset | `integer` |

### Returns
- `Pointer` <`Vtx`>

### C Prototype
`Vtx *vtx_get_vertex(Vtx *vtx, u32 offset);`
