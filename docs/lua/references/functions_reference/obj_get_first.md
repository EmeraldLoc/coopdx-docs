
## [obj_get_first](#obj_get_first)

### Description
Gets the first object in an object list

### Lua Example
`local objectValue = obj_get_first(objList)`

### Parameters
| Field | Type |
| ----- | ---- |
| objList | [enum ObjectList](constants.md#enum-ObjectList) |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *obj_get_first(enum ObjectList objList);`
