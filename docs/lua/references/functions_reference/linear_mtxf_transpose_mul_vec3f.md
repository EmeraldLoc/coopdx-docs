
## [linear_mtxf_transpose_mul_vec3f](#linear_mtxf_transpose_mul_vec3f)

### Description
Multiplies a vector by the transpose of a matrix of the form:
`| ? ? ? 0 |`
`| ? ? ? 0 |`
`| ? ? ? 0 |`
`| 0 0 0 1 |`
i.e. a matrix representing a linear transformation over 3 space

### Lua Example
`linear_mtxf_transpose_mul_vec3f(m, dst, v)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [Mat4](structs.md#Mat4) |
| dst | [Vec3f](structs.md#Vec3f) |
| v | [Vec3f](structs.md#Vec3f) |

### Returns
- None

### C Prototype
`void linear_mtxf_transpose_mul_vec3f(Mat4 m, VEC_OUT Vec3f dst, Vec3f v);`
