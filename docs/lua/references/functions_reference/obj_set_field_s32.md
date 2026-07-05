
## [obj_set_field_s32](#obj_set_field_s32)

### Description
Sets the signed 32-bit integer value of the object field corresponding to `fieldIndex`

### Lua Example
`obj_set_field_s32(o, fieldIndex, value)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| fieldIndex | `integer` |
| value | `integer` |

### Returns
- None

### C Prototype
`void obj_set_field_s32(struct Object *o, s32 fieldIndex, s32 value);`
