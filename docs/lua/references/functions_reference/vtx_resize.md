
## [vtx_resize](#vtx_resize)

### Description
Resizes a vertex buffer created by `vtx_create`

### Lua Example
`vtx_resize(vtx, newCount)`

### Parameters
| Field | Type |
| ----- | ---- |
| vtx | `Pointer` <`Vtx`> |
| newCount | `integer` |

### Returns
- None

### C Prototype
`void vtx_resize(Vtx *vtx, u32 newCount);`
