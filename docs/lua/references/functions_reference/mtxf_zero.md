
## [mtxf_zero](#mtxf_zero)

### Description
Sets the 4x4 floating-point matrix `mtx` to all zeros.
Unless you really need this-It's reccomended to use mtxf_identity instead.

### Lua Example
`mtxf_zero(mtx)`

### Parameters
| Field | Type |
| ----- | ---- |
| mtx | [Mat4](structs.md#Mat4) |

### Returns
- None

### C Prototype
`void mtxf_zero(VEC_OUT Mat4 mtx);`
