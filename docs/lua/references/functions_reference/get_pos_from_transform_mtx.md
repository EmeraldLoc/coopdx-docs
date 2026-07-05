
## [get_pos_from_transform_mtx](#get_pos_from_transform_mtx)

### Description
Extracts the position (translation component) from the transformation matrix `objMtx` relative to the coordinate system defined by `camMtx` and stores that 3D position in `dest`. This can be used to get the object's coordinates in camera space

### Lua Example
`local vec3fValue = get_pos_from_transform_mtx(dest, objMtx, camMtx)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| objMtx | [Mat4](structs.md#Mat4) |
| camMtx | [Mat4](structs.md#Mat4) |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp get_pos_from_transform_mtx(VEC_OUT Vec3f dest, Mat4 objMtx, Mat4 camMtx);`
