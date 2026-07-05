
## [mtxf_inverse](#mtxf_inverse)

### Description
Inverts the 4x4 floating-point matrix `src` and stores the inverse in `dest`. Applying the inverse transformation undoes whatever `src` did, returning points back to their original coordinate space. The `src` matrix *must* be affine!

### Lua Example
`mtxf_inverse(dest, src)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Mat4](structs.md#Mat4) |
| src | [Mat4](structs.md#Mat4) |

### Returns
- None

### C Prototype
`void mtxf_inverse(VEC_OUT Mat4 dest, Mat4 src);`
