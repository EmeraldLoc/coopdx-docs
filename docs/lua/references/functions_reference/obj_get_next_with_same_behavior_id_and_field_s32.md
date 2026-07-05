
## [obj_get_next_with_same_behavior_id_and_field_s32](#obj_get_next_with_same_behavior_id_and_field_s32)

### Description
Gets the next object loaded with the same behavior ID and object signed 32-bit integer field
(look in `object_fields.h` to get the index of a field)

### Lua Example
`local objectValue = obj_get_next_with_same_behavior_id_and_field_s32(o, fieldIndex, value)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| fieldIndex | `integer` |
| value | `integer` |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *obj_get_next_with_same_behavior_id_and_field_s32(struct Object *o, s32 fieldIndex, s32 value);`
