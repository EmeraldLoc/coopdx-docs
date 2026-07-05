
## [mtxf_mul](#mtxf_mul)

### Description
Multiplies two 4x4 floating-point matrices `a` and `b` (in that order), storing the product in `dest`. This can be used for combining multiple transformations into one

### Lua Example
`mtxf_mul(dest, a, b)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Mat4](structs.md#Mat4) |
| a | [Mat4](structs.md#Mat4) |
| b | [Mat4](structs.md#Mat4) |

### Returns
- None

### C Prototype
`void mtxf_mul(VEC_OUT Mat4 dest, Mat4 a, Mat4 b);`
