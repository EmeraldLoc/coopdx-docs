
## [obj_get_collided_object](#obj_get_collided_object)

### Description
Gets the corresponding collided object to an index from `o`

### Lua Example
`local objectValue = obj_get_collided_object(o, index)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| index | `integer` |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *obj_get_collided_object(struct Object *o, s16 index);`
