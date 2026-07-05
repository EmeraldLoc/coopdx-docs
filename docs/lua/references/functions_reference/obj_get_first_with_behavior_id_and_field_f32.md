
## [obj_get_first_with_behavior_id_and_field_f32](#obj_get_first_with_behavior_id_and_field_f32)

### Description
Gets the first object loaded with `behaviorId` and object float field
(look in `object_fields.h` to get the index of a field)

### Lua Example
`local objectValue = obj_get_first_with_behavior_id_and_field_f32(behaviorId, fieldIndex, value)`

### Parameters
| Field | Type |
| ----- | ---- |
| behaviorId | [enum BehaviorId](constants.md#enum-BehaviorId) |
| fieldIndex | `integer` |
| value | `number` |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *obj_get_first_with_behavior_id_and_field_f32(enum BehaviorId behaviorId, s32 fieldIndex, f32 value);`
