
## [bhv_spawn_star_no_level_exit](#bhv_spawn_star_no_level_exit)

### Description
Spawns a Star parented to `object` that won't make Mario exit the level with an ID corresponding to `params`' first byte

### Lua Example
`bhv_spawn_star_no_level_exit(object, params, networkSendEvent)`

### Parameters
| Field | Type |
| ----- | ---- |
| object | [Object](structs.md#Object) |
| params | `integer` |
| networkSendEvent | `integer` |

### Returns
- None

### C Prototype
`void bhv_spawn_star_no_level_exit(struct Object* object, u32 params, u8 networkSendEvent);`
