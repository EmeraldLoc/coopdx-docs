
## [random_vec3s](#random_vec3s)

### Description
Generates a random 3D vector with short integer components.
Useful for randomized offsets or environmental effects

### Lua Example
`random_vec3s(dst, xRange, yRange, zRange)`

### Parameters
| Field | Type |
| ----- | ---- |
| dst | [Vec3s](structs.md#Vec3s) |
| xRange | `integer` |
| yRange | `integer` |
| zRange | `integer` |

### Returns
- None

### C Prototype
`void random_vec3s(VEC_OUT Vec3s dst, s16 xRange, s16 yRange, s16 zRange);`
