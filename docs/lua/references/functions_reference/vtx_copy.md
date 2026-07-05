
## [vtx_copy](#vtx_copy)

### Description
Copies `count` vertices from vertex buffer `src` to vertex buffer `dest`

### Lua Example
`vtx_copy(dest, src, count)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | `Pointer` <`Vtx`> |
| src | `Pointer` <`Vtx`> |
| count | `integer` |

### Returns
- None

### C Prototype
`void vtx_copy(Vtx *dest, Vtx *src, u32 count);`
