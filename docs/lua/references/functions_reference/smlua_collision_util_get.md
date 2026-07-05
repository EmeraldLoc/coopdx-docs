
## [smlua_collision_util_get](#smlua_collision_util_get)

### Description
Gets the `Collision` with `name`

### Lua Example
`local pointerValue = smlua_collision_util_get(name)`

### Parameters
| Field | Type |
| ----- | ---- |
| name | `string` |

### Returns
- `Pointer` <`Collision`>

### C Prototype
`Collision* smlua_collision_util_get(const char* name);`
