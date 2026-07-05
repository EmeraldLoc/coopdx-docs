
## [obj_set_field_s16](#obj_set_field_s16)

### Description
Sets the signed 16-bit integer value of the object field and sub field corresponding to `fieldSubIndex` and `fieldIndex`

### Lua Example
`obj_set_field_s16(o, fieldIndex, fieldSubIndex, value)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| fieldIndex | `integer` |
| fieldSubIndex | `integer` |
| value | `integer` |

### Returns
- None

### C Prototype
`void obj_set_field_s16(struct Object *o, s32 fieldIndex, s32 fieldSubIndex, s16 value);`
