
## [mtxf_rotate_xyz_and_translate](#mtxf_rotate_xyz_and_translate)

### Description
Rotates `dest` using angles in XYZ order, and then translates it by the 3D floating-point vector `b` and applies the rotations described by `c`. This sets up `dest` with a specific orientation and position in space

### Lua Example
`mtxf_rotate_xyz_and_translate(dest, b, c)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Mat4](structs.md#Mat4) |
| b | [Vec3f](structs.md#Vec3f) |
| c | [Vec3s](structs.md#Vec3s) |

### Returns
- None

### C Prototype
`void mtxf_rotate_xyz_and_translate(VEC_OUT Mat4 dest, Vec3f b, Vec3s c);`
