
## [get_mod_files](#get_mod_files)

### Description
Gets all files a mod contains

### Lua Example
`local tableValue = get_mod_files(mod, subDirectory)`

### Parameters
| Field | Type |
| ----- | ---- |
| mod | [Mod](structs.md#Mod) |
| subDirectory | `string` |

### Returns
- `table`

### C Prototype
`LuaTable get_mod_files(struct Mod* mod, OPTIONAL const char* subDirectory);`
