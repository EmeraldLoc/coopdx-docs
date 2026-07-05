
## [calc_hor_dist](#calc_hor_dist)

### Description
Calculates the horizontal (XZ-plane) distance between two 3D points (`a` and `b`).
Returns the distance as a floating-point value.
Useful for terrain navigation or collision detection

### Lua Example
`local numberValue = calc_hor_dist(a, b)`

### Parameters
| Field | Type |
| ----- | ---- |
| a | [Vec3f](structs.md#Vec3f) |
| b | [Vec3f](structs.md#Vec3f) |

### Returns
- `number`

### C Prototype
`f32 calc_hor_dist(Vec3f a, Vec3f b);`
