
## [obj_get_first_with_behavior_id](#obj_get_first_with_behavior_id)

### Description
Gets the first object loaded with `behaviorId`

### Lua Example
`local objectValue = obj_get_first_with_behavior_id(behaviorId)`

### Parameters
| Field | Type |
| ----- | ---- |
| behaviorId | [enum BehaviorId](constants.md#enum-BehaviorId) |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *obj_get_first_with_behavior_id(enum BehaviorId behaviorId);`
