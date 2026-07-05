
## [is_nearest_player_to_object](#is_nearest_player_to_object)

### Description
Checks if `m` is the nearest player (Mario Object) to `obj`

### Lua Example
`local integerValue = is_nearest_player_to_object(m, obj)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [Object](structs.md#Object) |
| obj | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u8 is_nearest_player_to_object(struct Object *m, struct Object *obj);`
