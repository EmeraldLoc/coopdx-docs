
## [obj_get_next_with_same_behavior_id_and_field_f32](#obj_get_next_with_same_behavior_id_and_field_f32)

### Description
Gets the next object loaded with the same behavior ID and object float field
(look in `object_fields.h` to get the index of a field)

### Lua Example
`local objectValue = obj_get_next_with_same_behavior_id_and_field_f32(o, fieldIndex, value)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| fieldIndex | `integer` |
| value | `number` |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *obj_get_next_with_same_behavior_id_and_field_f32(struct Object *o, s32 fieldIndex, f32 value);`
