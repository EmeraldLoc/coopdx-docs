
## [le_calculate_lighting_color](#le_calculate_lighting_color)

### Description
Calculates the lighting with `lightIntensityScalar` at a position and outputs the color in `out`

### Lua Example
`le_calculate_lighting_color(pos, out, lightIntensityScalar)`

### Parameters
| Field | Type |
| ----- | ---- |
| pos | [Vec3f](structs.md#Vec3f) |
| out | [Color](structs.md#Color) |
| lightIntensityScalar | `number` |

### Returns
- None

### C Prototype
`void le_calculate_lighting_color(Vec3f pos, VEC_OUT Color out, f32 lightIntensityScalar);`
