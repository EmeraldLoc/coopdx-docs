
## [delta_interpolate_vec3f](#delta_interpolate_vec3f)

### Description
Linearly interpolates `res` between `a` and `b` with `delta`

### Lua Example
`delta_interpolate_vec3f(res, a, b, delta)`

### Parameters
| Field | Type |
| ----- | ---- |
| res | [Vec3f](structs.md#Vec3f) |
| a | [Vec3f](structs.md#Vec3f) |
| b | [Vec3f](structs.md#Vec3f) |
| delta | `number` |

### Returns
- None

### C Prototype
`void delta_interpolate_vec3f(VEC_OUT Vec3f res, Vec3f a, Vec3f b, f32 delta);`
