
## [obj_get_nearest_object_with_behavior_id](#obj_get_nearest_object_with_behavior_id)

### Description
Gets the nearest object with `behaviorId` to `o`

### Lua Example
`local objectValue = obj_get_nearest_object_with_behavior_id(o, behaviorId)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| behaviorId | [enum BehaviorId](constants.md#enum-BehaviorId) |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *obj_get_nearest_object_with_behavior_id(struct Object *o, enum BehaviorId behaviorId);`
