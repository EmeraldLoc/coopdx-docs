
## [cur_obj_nearest_object_with_behavior](#cur_obj_nearest_object_with_behavior)

### Description
Finds the nearest object with the specified behavior to the current object

### Lua Example
`local objectValue = cur_obj_nearest_object_with_behavior(behavior)`

### Parameters
| Field | Type |
| ----- | ---- |
| behavior | `Pointer` <`BehaviorScript`> |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *cur_obj_nearest_object_with_behavior(const BehaviorScript *behavior);`
