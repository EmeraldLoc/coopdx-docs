
## [smlua_collision_util_get_level_collision](#smlua_collision_util_get_level_collision)

### Description
Gets the `level` terrain collision from `area`

### Lua Example
`local pointerValue = smlua_collision_util_get_level_collision(level, area)`

### Parameters
| Field | Type |
| ----- | ---- |
| level | `integer` |
| area | `integer` |

### Returns
- `Pointer` <`Collision`>

### C Prototype
`Collision *smlua_collision_util_get_level_collision(u32 level, u16 area);`
