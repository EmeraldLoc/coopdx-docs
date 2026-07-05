
## [obj_get_field_s16](#obj_get_field_s16)

### Description
Gets the signed 16-bit integer value of the object field and sub field corresponding to `fieldSubIndex` and `fieldIndex`

### Lua Example
`local integerValue = obj_get_field_s16(o, fieldIndex, fieldSubIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| fieldIndex | `integer` |
| fieldSubIndex | `integer` |

### Returns
- `integer`

### C Prototype
`s16 obj_get_field_s16(struct Object *o, s32 fieldIndex, s32 fieldSubIndex);`
