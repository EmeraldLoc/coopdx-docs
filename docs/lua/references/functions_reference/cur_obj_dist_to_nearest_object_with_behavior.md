
## [cur_obj_dist_to_nearest_object_with_behavior](#cur_obj_dist_to_nearest_object_with_behavior)

### Description
Calculates the distance from the current object to the nearest object with specified behavior

### Lua Example
`local numberValue = cur_obj_dist_to_nearest_object_with_behavior(behavior)`

### Parameters
| Field | Type |
| ----- | ---- |
| behavior | `Pointer` <`BehaviorScript`> |

### Returns
- `number`

### C Prototype
`f32 cur_obj_dist_to_nearest_object_with_behavior(const BehaviorScript *behavior);`
