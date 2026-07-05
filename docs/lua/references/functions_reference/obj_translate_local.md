
## [obj_translate_local](#obj_translate_local)

### Description
Transforms the vector at `localTranslateIndex` into the object's local coordinates, and then adds it to the vector at `posIndex`

### Lua Example
`obj_translate_local(obj, posIndex, localTranslateIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |
| posIndex | `integer` |
| localTranslateIndex | `integer` |

### Returns
- None

### C Prototype
`void obj_translate_local(struct Object *obj, s16 posIndex, s16 localTranslateIndex);`
