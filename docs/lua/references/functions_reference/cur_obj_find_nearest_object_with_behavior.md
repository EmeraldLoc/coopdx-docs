
## [cur_obj_find_nearest_object_with_behavior](#cur_obj_find_nearest_object_with_behavior)

### Description
Finds the nearest object with specified behavior and returns distance via pointer

### Lua Example
`local objectValue, dist = cur_obj_find_nearest_object_with_behavior(behavior)`

### Parameters
| Field | Type |
| ----- | ---- |
| behavior | `Pointer` <`BehaviorScript`> |

### Returns
- [Object](structs.md#Object)
- `number`

### C Prototype
`struct Object *cur_obj_find_nearest_object_with_behavior(const BehaviorScript *behavior, RET f32 *dist);`
