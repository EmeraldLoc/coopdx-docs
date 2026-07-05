
## [obj_get_next_with_same_behavior_id](#obj_get_next_with_same_behavior_id)

### Description
Gets the next object loaded with the same behavior ID

### Lua Example
`local objectValue = obj_get_next_with_same_behavior_id(o)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *obj_get_next_with_same_behavior_id(struct Object *o);`
