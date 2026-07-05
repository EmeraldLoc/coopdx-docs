
## [gfx_parse](#gfx_parse)

### Description
Traverses a display list. Takes a Lua function as a parameter, which is called back for each command in the display list with the parameters `cmd` (display list pointer), and `op`

### Lua Example
`gfx_parse(cmd, func)`

### Parameters
| Field | Type |
| ----- | ---- |
| cmd | `Pointer` <`Gfx`> |
| func | `Lua Function` () |

### Returns
- None

### C Prototype
`void gfx_parse(Gfx *cmd, LuaFunction func);`
