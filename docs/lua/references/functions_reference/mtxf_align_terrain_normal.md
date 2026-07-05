
## [mtxf_align_terrain_normal](#mtxf_align_terrain_normal)

### Description
Aligns `dest` so that it fits the orientation of a terrain surface defined by its normal vector `upDir`. The transformation is positioned at `pos` and oriented with a given `yaw`. This is often used to make objects sit naturally on uneven ground

### Lua Example
`mtxf_align_terrain_normal(dest, upDir, pos, yaw)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Mat4](structs.md#Mat4) |
| upDir | [Vec3f](structs.md#Vec3f) |
| pos | [Vec3f](structs.md#Vec3f) |
| yaw | `integer` |

### Returns
- None

### C Prototype
`void mtxf_align_terrain_normal(VEC_OUT Mat4 dest, Vec3f upDir, Vec3f pos, s16 yaw);`
