
## [spawn_star_with_no_lvl_exit](#spawn_star_with_no_lvl_exit)

### Description
Spawns a star object without triggering level exit behavior

### Lua Example
`local objectValue = spawn_star_with_no_lvl_exit(setHomeToMario, unused)`

### Parameters
| Field | Type |
| ----- | ---- |
| setHomeToMario | `integer` |
| unused | `integer` |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *spawn_star_with_no_lvl_exit(s32 setHomeToMario, s32 unused);`
