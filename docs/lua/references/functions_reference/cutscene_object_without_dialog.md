
## [cutscene_object_without_dialog](#cutscene_object_without_dialog)

### Description
Starts a cutscene involving an object without dialog.
The camera transitions smoothly to focus on the object

### Lua Example
`local integerValue = cutscene_object_without_dialog(cutscene, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| cutscene | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`s16 cutscene_object_without_dialog(u8 cutscene, struct Object *o);`
