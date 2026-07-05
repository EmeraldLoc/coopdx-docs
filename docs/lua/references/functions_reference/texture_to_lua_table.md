
## [texture_to_lua_table](#texture_to_lua_table)

### Description
Converts a texture's pixels to a Lua table. Returns nil if failed. Otherwise, returns a 1-indexed table of RGBA pixels

### Lua Example
`local tableValue = texture_to_lua_table(tex)`

### Parameters
| Field | Type |
| ----- | ---- |
| tex | `Pointer` <`Texture`> |

### Returns
- `table`

### C Prototype
`LuaTable texture_to_lua_table(const Texture *tex);`
