
## [obj_is_mario_ground_pounding_platform](#obj_is_mario_ground_pounding_platform)

### Description
Checks whether a MarioState is ground-pounding the specified platform object

### Lua Example
`local integerValue = obj_is_mario_ground_pounding_platform(m, obj)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| obj | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`s32 obj_is_mario_ground_pounding_platform(struct MarioState *m, struct Object *obj);`
