
## [mtxf_copy](#mtxf_copy)

### Description
Copies the 4x4 floating-point matrix `src` into `dest`. After this operation, `dest` contains the same matrix values as `src`

### Lua Example
`mtxf_copy(dest, src)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Mat4](structs.md#Mat4) |
| src | [Mat4](structs.md#Mat4) |

### Returns
- None

### C Prototype
`void mtxf_copy(VEC_OUT Mat4 dest, Mat4 src);`
