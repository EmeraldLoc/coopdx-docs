
## [obj_get_first_with_behavior_id_and_field_s32](#obj_get_first_with_behavior_id_and_field_s32)

### Description
Gets the first object loaded with `behaviorId` and object signed 32-bit integer field
(look in `object_fields.h` to get the index of a field)

### Lua Example
`local objectValue = obj_get_first_with_behavior_id_and_field_s32(behaviorId, fieldIndex, value)`

### Parameters
| Field | Type |
| ----- | ---- |
| behaviorId | [enum BehaviorId](constants.md#enum-BehaviorId) |
| fieldIndex | `integer` |
| value | `integer` |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *obj_get_first_with_behavior_id_and_field_s32(enum BehaviorId behaviorId, s32 fieldIndex, s32 value);`
