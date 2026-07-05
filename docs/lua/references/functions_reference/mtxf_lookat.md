
## [mtxf_lookat](#mtxf_lookat)

### Description
Adjusts the 4x4 floating-point matrix `mtx` so that it represents a viewing transformation looking from the point `from` toward the point `to`, with a given roll angle. This creates a view matrix oriented toward `to`

### Lua Example
`mtxf_lookat(mtx, from, to, roll)`

### Parameters
| Field | Type |
| ----- | ---- |
| mtx | [Mat4](structs.md#Mat4) |
| from | [Vec3f](structs.md#Vec3f) |
| to | [Vec3f](structs.md#Vec3f) |
| roll | `integer` |

### Returns
- None

### C Prototype
`void mtxf_lookat(VEC_OUT Mat4 mtx, Vec3f from, Vec3f to, s16 roll);`
