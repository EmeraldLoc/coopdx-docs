
## [mtxf_rotate_zxy_and_translate](#mtxf_rotate_zxy_and_translate)

### Description
Rotates `dest` according to the angles in `rotate` using ZXY order, and then translates it by the 3D floating-point vector `translate`. This effectively positions and orients `dest` in 3D space

### Lua Example
`mtxf_rotate_zxy_and_translate(dest, translate, rotate)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Mat4](structs.md#Mat4) |
| translate | [Vec3f](structs.md#Vec3f) |
| rotate | [Vec3s](structs.md#Vec3s) |

### Returns
- None

### C Prototype
`void mtxf_rotate_zxy_and_translate(VEC_OUT Mat4 dest, Vec3f translate, Vec3s rotate);`
