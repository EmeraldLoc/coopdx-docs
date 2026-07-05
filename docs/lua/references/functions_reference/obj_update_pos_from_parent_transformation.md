
## [obj_update_pos_from_parent_transformation](#obj_update_pos_from_parent_transformation)

### Description
Updates an object's position based on a parent transformation matrix

### Lua Example
`obj_update_pos_from_parent_transformation(mtx, obj)`

### Parameters
| Field | Type |
| ----- | ---- |
| mtx | [Mat4](structs.md#Mat4) |
| obj | [Object](structs.md#Object) |

### Returns
- None

### C Prototype
`void obj_update_pos_from_parent_transformation(Mat4 mtx, struct Object *obj);`
