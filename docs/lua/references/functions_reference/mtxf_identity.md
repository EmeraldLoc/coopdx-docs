
## [mtxf_identity](#mtxf_identity)

### Description
Sets the 4x4 floating-point matrix `mtx` to the identity matrix. The identity matrix leaves points unchanged when they are transformed by it which is useful for matrix math

### Lua Example
`mtxf_identity(mtx)`

### Parameters
| Field | Type |
| ----- | ---- |
| mtx | [Mat4](structs.md#Mat4) |

### Returns
- None

### C Prototype
`void mtxf_identity(VEC_OUT Mat4 mtx);`
