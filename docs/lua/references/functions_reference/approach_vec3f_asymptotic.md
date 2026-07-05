
## [approach_vec3f_asymptotic](#approach_vec3f_asymptotic)

### Description
Smoothly transitions a 3D vector (`current`) towards a target vector (`target`) using asymptotic scaling.
Scaling values (the `Mul` variables) for x, y, and z axes determine the speed of adjustment for each component

### Lua Example
`approach_vec3f_asymptotic(current, target, xMul, yMul, zMul)`

### Parameters
| Field | Type |
| ----- | ---- |
| current | [Vec3f](structs.md#Vec3f) |
| target | [Vec3f](structs.md#Vec3f) |
| xMul | `number` |
| yMul | `number` |
| zMul | `number` |

### Returns
- None

### C Prototype
`void approach_vec3f_asymptotic(VEC_OUT Vec3f current, Vec3f target, f32 xMul, f32 yMul, f32 zMul);`
