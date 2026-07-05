
## [mtxf_cylboard](#mtxf_cylboard)

### Description
Creates a "cylindrical billboard" transformation from the 4x4 matrix `mtx` placed at `position` with a given `angle`. Unlike a full billboard, this might allow rotation around one axis while still facing the viewer on others

### Lua Example
`mtxf_cylboard(dest, mtx, position, angle)`

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
`void mtxf_cylboard(VEC_OUT Mat4 dest, Mat4 mtx, Vec3f position, s16 angle);`
