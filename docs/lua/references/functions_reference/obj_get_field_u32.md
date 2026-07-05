
## [obj_get_field_u32](#obj_get_field_u32)

### Description
Gets the unsigned 32-bit integer value of the object field corresponding to `fieldIndex`

### Lua Example
`local integerValue = obj_get_field_u32(o, fieldIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| fieldIndex | `integer` |

### Returns
- `integer`

### C Prototype
`u32 obj_get_field_u32(struct Object *o, s32 fieldIndex);`
