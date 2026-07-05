
## [cutscene_object_with_dialog](#cutscene_object_with_dialog)

### Description
Starts a cutscene involving an object and displays dialog during the sequence.
The camera focuses on the object while synchronizing dialog with the scene

### Lua Example
`local integerValue = cutscene_object_with_dialog(cutscene, o, dialogID)`

### Parameters
| Field | Type |
| ----- | ---- |
| cutscene | `integer` |
| o | [Object](structs.md#Object) |
| dialogID | `integer` |

### Returns
- `integer`

### C Prototype
`s16 cutscene_object_with_dialog(u8 cutscene, struct Object *o, s32 dialogID);`
