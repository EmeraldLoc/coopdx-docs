
## [lvl_set_current_level](#lvl_set_current_level)

### Description
Sets the level number and handles the act select screen. `param` is used for overriding the level ID in level scripts, set to 0 in Lua

### Lua Example
`local integerValue = lvl_set_current_level(param, levelNum)`

### Parameters
| Field | Type |
| ----- | ---- |
| param | `integer` |
| levelNum | `integer` |

### Returns
- `integer`

### C Prototype
`s32 lvl_set_current_level(s16 param, s16 levelNum);`
