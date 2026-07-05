
## [vtx_get_next_vertex](#vtx_get_next_vertex)

### Description
Gets the next vertex of a given vertex pointer. Intended to use in a for loop

### Lua Example
`local pointerValue = vtx_get_next_vertex(vtx)`

### Parameters
| Field | Type |
| ----- | ---- |
| vtx | `Pointer` <`Vtx`> |

### Returns
- `Pointer` <`Vtx`>

### C Prototype
`Vtx *vtx_get_next_vertex(Vtx *vtx);`
