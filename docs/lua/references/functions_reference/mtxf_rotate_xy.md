
## [mtxf_rotate_xy](#mtxf_rotate_xy)

### Description
Rotates the matrix `mtx` in the XY plane by the given `angle`. Rotating in the XY plane typically means pivoting around the Z axis

### Lua Example
`mtxf_rotate_xy(mtx, angle)`

### Parameters
| Field | Type |
| ----- | ---- |
| mtx | [Mat4](structs.md#Mat4) |
| angle | `integer` |

### Returns
- None

### C Prototype
`void mtxf_rotate_xy(VEC_OUT Mat4 mtx, s16 angle);`
