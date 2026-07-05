
## [mtxf_billboard](#mtxf_billboard)

### Description
Transforms a 4x4 floating-point matrix `mtx` into a "billboard" oriented toward the camera or a given direction. The billboard is placed at `position` and rotated by `angle`. This is useful for objects that should always face the viewer

### Lua Example
`mtxf_billboard(dest, mtx, position, angle)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Mat4](structs.md#Mat4) |
| mtx | [Mat4](structs.md#Mat4) |
| position | [Vec3f](structs.md#Vec3f) |
| angle | `integer` |

### Returns
- None

### C Prototype
`void mtxf_billboard(VEC_OUT Mat4 dest, Mat4 mtx, Vec3f position, s16 angle);`
