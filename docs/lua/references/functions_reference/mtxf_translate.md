
## [mtxf_translate](#mtxf_translate)

### Description
Sets the 4x4 floating-point matrix `dest` to the translation matrix decribed by the 3D floating-point vector `b`. This matrix is used to shift any transformed point by `b`

### Lua Example
`mtxf_translate(dest, b)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Mat4](structs.md#Mat4) |
| b | [Vec3f](structs.md#Vec3f) |

### Returns
- None

### C Prototype
`void mtxf_translate(VEC_OUT Mat4 dest, Vec3f b);`
