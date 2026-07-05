
## [obj_has_behavior_id](#obj_has_behavior_id)

### Description
Checks if an object has `behaviorId`

### Lua Example
`local integerValue = obj_has_behavior_id(o, behaviorId)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| behaviorId | [enum BehaviorId](constants.md#enum-BehaviorId) |

### Returns
- `integer`

### C Prototype
`s32 obj_has_behavior_id(struct Object *o, enum BehaviorId behaviorId);`
