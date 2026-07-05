
## [gfx_copy](#gfx_copy)

### Description
Copies `length` commands from display list `src` to display list `dest`

### Lua Example
`gfx_copy(dest, src, length)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | `Pointer` <`Gfx`> |
| src | `Pointer` <`Gfx`> |
| length | `integer` |

### Returns
- None

### C Prototype
`void gfx_copy(Gfx *dest, Gfx *src, u32 length);`
