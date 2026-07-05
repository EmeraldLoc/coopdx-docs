
## [nearest_player_to_object](#nearest_player_to_object)

### Description
Gets the nearest player (Mario Object) to `obj`

### Lua Example
`local objectValue = nearest_player_to_object(obj)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object* nearest_player_to_object(struct Object *obj);`
