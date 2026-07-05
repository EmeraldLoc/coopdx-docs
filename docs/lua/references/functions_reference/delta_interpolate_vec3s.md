
## [delta_interpolate_vec3s](#delta_interpolate_vec3s)

### Description
Linearly interpolates `res` between `a` and `b` with `delta`

### Lua Example
`delta_interpolate_vec3s(res, a, b, delta)`

### Parameters
| Field | Type |
| ----- | ---- |
| res | [Vec3s](structs.md#Vec3s) |
| a | [Vec3s](structs.md#Vec3s) |
| b | [Vec3s](structs.md#Vec3s) |
| delta | `number` |

### Returns
- None

### C Prototype
`void delta_interpolate_vec3s(VEC_OUT Vec3s res, Vec3s a, Vec3s b, f32 delta);`
