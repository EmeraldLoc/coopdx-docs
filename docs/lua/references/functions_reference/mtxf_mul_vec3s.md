
## [mtxf_mul_vec3s](#mtxf_mul_vec3s)

### Description
Multiplies the 3D signed-integer vector `b` with the 4x4 floating-point matrix `mtx`, which applies the transformation to the point

### Lua Example
`local vec3sValue = mtxf_mul_vec3s(mtx, b)`

### Parameters
| Field | Type |
| ----- | ---- |
| mtx | [Mat4](structs.md#Mat4) |
| b | [Vec3s](structs.md#Vec3s) |

### Returns
- [Vec3s](structs.md#Vec3s)

### C Prototype
`Vec3sp mtxf_mul_vec3s(Mat4 mtx, VEC_OUT Vec3s b);`
