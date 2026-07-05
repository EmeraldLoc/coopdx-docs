
## [obj_attack_collided_from_other_object](#obj_attack_collided_from_other_object)

### Description
Marks another object as attacked by the current object and returns whether it collided

### Lua Example
`local integerValue = obj_attack_collided_from_other_object(obj)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`s32 obj_attack_collided_from_other_object(struct Object *obj);`
