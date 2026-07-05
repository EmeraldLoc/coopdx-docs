
## [vtx_get_from_name](#vtx_get_from_name)

### Description
Gets a vertex buffer of the current mod from its name.
Returns a pointer to the vertex buffer and its vertex count

### Lua Example
`local pointerValue, count = vtx_get_from_name(name)`

### Parameters
| Field | Type |
| ----- | ---- |
| name | `string` |

### Returns
- `Pointer` <`Vtx`>
- `integer`

### C Prototype
`Vtx *vtx_get_from_name(const char *name, RET u32 *count);`
