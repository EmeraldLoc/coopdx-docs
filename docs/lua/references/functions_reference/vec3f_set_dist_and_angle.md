
## [vec3f_set_dist_and_angle](#vec3f_set_dist_and_angle)

### Description
Positions the point `to` at a given `dist`, `pitch`, and `yaw` relative to the point `from`. This can be used to place objects around a reference point at specific angles and distances

### Lua Example
`vec3f_set_dist_and_angle(from, to, dist, pitch, yaw)`

### Parameters
| Field | Type |
| ----- | ---- |
| from | [Vec3f](structs.md#Vec3f) |
| to | [Vec3f](structs.md#Vec3f) |
| dist | `number` |
| pitch | `integer` |
| yaw | `integer` |

### Returns
- None

### C Prototype
`void vec3f_set_dist_and_angle(Vec3f from, VEC_OUT Vec3f to, f32 dist, s16 pitch, s16 yaw);`
