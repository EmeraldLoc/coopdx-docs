
## [obj_has_model_extended](#obj_has_model_extended)

### Description
Checks if an object's model is equal to `modelId`

### Lua Example
`local integerValue = obj_has_model_extended(o, modelId)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| modelId | [enum ModelExtendedId](constants.md#enum-ModelExtendedId) |

### Returns
- `integer`

### C Prototype
`s32 obj_has_model_extended(struct Object *o, enum ModelExtendedId modelId);`
