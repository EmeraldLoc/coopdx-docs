
## [clamp_positions_and_find_yaw](#clamp_positions_and_find_yaw)

### Description
Clamps a position within specified X and Z bounds and calculates the yaw angle from the origin.
Prevents the camera from moving outside of the designated area

### Lua Example
`local integerValue = clamp_positions_and_find_yaw(pos, origin, xMax, xMin, zMax, zMin)`

### Parameters
| Field | Type |
| ----- | ---- |
| pos | [Vec3f](structs.md#Vec3f) |
| origin | [Vec3f](structs.md#Vec3f) |
| xMax | `number` |
| xMin | `number` |
| zMax | `number` |
| zMin | `number` |

### Returns
- `integer`

### C Prototype
`s32 clamp_positions_and_find_yaw(VEC_OUT Vec3f pos, Vec3f origin, f32 xMax, f32 xMin, f32 zMax, f32 zMin);`
