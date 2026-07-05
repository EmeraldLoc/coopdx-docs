
## [obj_get_next](#obj_get_next)

### Description
Gets the next object in an object list

### Lua Example
`local objectValue = obj_get_next(o)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *obj_get_next(struct Object *o);`
