
## [vec3f_get_dist_and_angle](#vec3f_get_dist_and_angle)

### Description
Calculates the distance between two points in 3D space (`from` and `to`), as well as the pitch and yaw angles that describe the direction from `from` to `to`. Returns the calculated distance, pitch and yaw

### Lua Example
`local dist, pitch, yaw = vec3f_get_dist_and_angle(from, to)`

### Parameters
| Field | Type |
| ----- | ---- |
| from | [Vec3f](structs.md#Vec3f) |
| to | [Vec3f](structs.md#Vec3f) |

### Returns
- `number`
- `integer`
- `integer`

### C Prototype
`void vec3f_get_dist_and_angle(Vec3f from, Vec3f to, RET f32 *dist, RET s16 *pitch, RET s16 *yaw);`
