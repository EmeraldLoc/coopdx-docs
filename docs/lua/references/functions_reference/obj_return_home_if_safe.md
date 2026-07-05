
## [obj_return_home_if_safe](#obj_return_home_if_safe)

### Description
Turns an object towards home if Mario is not near to it

### Lua Example
`local integerValue = obj_return_home_if_safe(obj, homeX, y, homeZ, dist)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |
| homeX | `number` |
| y | `number` |
| homeZ | `number` |
| dist | `integer` |

### Returns
- `integer`

### C Prototype
`s8 obj_return_home_if_safe(struct Object *obj, f32 homeX, f32 y, f32 homeZ, s32 dist);`
