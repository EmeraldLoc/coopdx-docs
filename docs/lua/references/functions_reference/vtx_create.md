
## [vtx_create](#vtx_create)

### Description
Creates a new named vertex buffer of `count` vertices

### Lua Example
`local pointerValue = vtx_create(name, count)`

### Parameters
| Field | Type |
| ----- | ---- |
| name | `string` |
| count | `integer` |

### Returns
- `Pointer` <`Vtx`>

### C Prototype
`Vtx *vtx_create(const char *name, u32 count);`
