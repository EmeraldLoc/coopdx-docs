
## [mtxf_inverse_non_affine](#mtxf_inverse_non_affine)

### Description
Inverts the 4x4 floating-point matrix `src` and stores the inverse in `dest`. Applying the inverse transformation undoes whatever `src` did, returning points back to their original coordinate space. Returns `false` if the inversion failed.

### Lua Example
`local booleanValue = mtxf_inverse_non_affine(dest, src)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Mat4](structs.md#Mat4) |
| src | [Mat4](structs.md#Mat4) |

### Returns
- `boolean`

### C Prototype
`bool mtxf_inverse_non_affine(VEC_OUT Mat4 dest, Mat4 src);`
