
## [mtxf_align_terrain_triangle](#mtxf_align_terrain_triangle)

### Description
Aligns `mtx` to fit onto a terrain triangle at `pos`, applying a given `yaw` and scaling by `radius`. This helps position objects so they match the orientation of the terrain's surface

### Lua Example
`mtxf_align_terrain_triangle(mtx, pos, yaw, radius)`

### Parameters
| Field | Type |
| ----- | ---- |
| mtx | [Mat4](structs.md#Mat4) |
| pos | [Vec3f](structs.md#Vec3f) |
| yaw | `integer` |
| radius | `number` |

### Returns
- None

### C Prototype
`void mtxf_align_terrain_triangle(VEC_OUT Mat4 mtx, Vec3f pos, s16 yaw, f32 radius);`
