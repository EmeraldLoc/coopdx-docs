
## [calc_abs_dist](#calc_abs_dist)

### Description
Calculates the absolute distance between two 3D points (`a` and `b`).
Returns the distance as a floating-point value.
Useful for determining proximity between objects in 3D space

### Lua Example
`local numberValue = calc_abs_dist(a, b)`

### Parameters
| Field | Type |
| ----- | ---- |
| a | [Vec3f](structs.md#Vec3f) |
| b | [Vec3f](structs.md#Vec3f) |

### Returns
- `number`

### C Prototype
`f32 calc_abs_dist(Vec3f a, Vec3f b);`
