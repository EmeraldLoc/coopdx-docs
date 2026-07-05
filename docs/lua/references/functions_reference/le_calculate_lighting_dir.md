
## [le_calculate_lighting_dir](#le_calculate_lighting_dir)

### Description
Calculates the lighting direction from a position and outputs the result in `out`

### Lua Example
`le_calculate_lighting_dir(pos, out)`

### Parameters
| Field | Type |
| ----- | ---- |
| pos | [Vec3f](structs.md#Vec3f) |
| out | [Vec3f](structs.md#Vec3f) |

### Returns
- None

### C Prototype
`void le_calculate_lighting_dir(Vec3f pos, VEC_OUT Vec3f out);`
