
## [obj_build_transform_from_pos_and_angle](#obj_build_transform_from_pos_and_angle)

### Description
Copies an object's position and rotation into its transform matrix using the specified field indices

### Lua Example
`obj_build_transform_from_pos_and_angle(obj, posIndex, angleIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |
| posIndex | `integer` |
| angleIndex | `integer` |

### Returns
- None

### C Prototype
`void obj_build_transform_from_pos_and_angle(struct Object *obj, s16 posIndex, s16 angleIndex);`
