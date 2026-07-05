
## [obj_apply_scale_to_matrix](#obj_apply_scale_to_matrix)

### Description
Applies an object's scale to a transformation matrix

### Lua Example
`obj_apply_scale_to_matrix(obj, dst, src)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |
| dst | [Mat4](structs.md#Mat4) |
| src | [Mat4](structs.md#Mat4) |

### Returns
- None

### C Prototype
`void obj_apply_scale_to_matrix(struct Object *obj, VEC_OUT Mat4 dst, Mat4 src);`
