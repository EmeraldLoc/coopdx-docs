
## [mtxf_scale_vec3f](#mtxf_scale_vec3f)

### Description
Scales the 4x4 floating-point matrix `mtx` by the scaling factors found in the 3D floating-point vector `s`, and stores the result in `dest`. This enlarges or shrinks objects in 3D space

### Lua Example
`mtxf_scale_vec3f(dest, mtx, s)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Mat4](structs.md#Mat4) |
| mtx | [Mat4](structs.md#Mat4) |
| s | [Vec3f](structs.md#Vec3f) |

### Returns
- None

### C Prototype
`void mtxf_scale_vec3f(VEC_OUT Mat4 dest, Mat4 mtx, Vec3f s);`
