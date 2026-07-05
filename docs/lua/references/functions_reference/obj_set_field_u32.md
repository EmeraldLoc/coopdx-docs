
## [obj_set_field_u32](#obj_set_field_u32)

### Description
Sets the unsigned 32-bit integer value of the object field corresponding to `fieldIndex`

### Lua Example
`obj_set_field_u32(o, fieldIndex, value)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| fieldIndex | `integer` |
| value | `integer` |

### Returns
- None

### C Prototype
`void obj_set_field_u32(struct Object *o, s32 fieldIndex, u32 value);`
