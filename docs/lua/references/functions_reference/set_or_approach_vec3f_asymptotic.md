
## [set_or_approach_vec3f_asymptotic](#set_or_approach_vec3f_asymptotic)

### Description
Smoothly transitions a 3D vector (`current`) toward a target vector (`goal`) using asymptotic scaling.
Allows gradual or instantaneous alignment of 3D positions. Scaling values (the `Mul` variables) for x, y, and z axes determine the speed of adjustment for each component

### Lua Example
`set_or_approach_vec3f_asymptotic(dst, goal, xMul, yMul, zMul)`

### Parameters
| Field | Type |
| ----- | ---- |
| dst | [Vec3f](structs.md#Vec3f) |
| goal | [Vec3f](structs.md#Vec3f) |
| xMul | `number` |
| yMul | `number` |
| zMul | `number` |

### Returns
- None

### C Prototype
`void set_or_approach_vec3f_asymptotic(VEC_OUT Vec3f dst, Vec3f goal, f32 xMul, f32 yMul, f32 zMul);`
