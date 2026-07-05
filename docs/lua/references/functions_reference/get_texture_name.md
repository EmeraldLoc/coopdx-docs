
## [get_texture_name](#get_texture_name)

### Description
Gets the name of the provided texture pointer `tex`

### Lua Example
`local stringValue = get_texture_name(tex)`

### Parameters
| Field | Type |
| ----- | ---- |
| tex | `Pointer` <`Texture`> |

### Returns
- `string`

### C Prototype
`const char *get_texture_name(const Texture *tex);`
