
## [obj_set_field_f32](#obj_set_field_f32)

### Description
Sets the float value of the object field corresponding to `fieldIndex`

### Lua Example
`obj_set_field_f32(o, fieldIndex, value)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| fieldIndex | `integer` |
| value | `number` |

### Returns
- None

### C Prototype
`void obj_set_field_f32(struct Object *o, s32 fieldIndex, f32 value);`
