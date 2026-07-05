
## [clamp_pitch](#clamp_pitch)

### Description
Clamps the camera's pitch angle between a maximum and minimum value.
Prevents over-rotation and maintains a consistent viewing angle

### Lua Example
`local integerValue = clamp_pitch(from, to, maxPitch, minPitch)`

### Parameters
| Field | Type |
| ----- | ---- |
| from | [Vec3f](structs.md#Vec3f) |
| to | [Vec3f](structs.md#Vec3f) |
| maxPitch | `integer` |
| minPitch | `integer` |

### Returns
- `integer`

### C Prototype
`s32 clamp_pitch(Vec3f from, VEC_OUT Vec3f to, s16 maxPitch, s16 minPitch);`
