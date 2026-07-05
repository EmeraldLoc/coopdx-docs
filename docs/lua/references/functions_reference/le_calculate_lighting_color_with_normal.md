
## [le_calculate_lighting_color_with_normal](#le_calculate_lighting_color_with_normal)

### Description
Calculates the lighting with `lightIntensityScalar` at a position and with a normal and outputs the color in `out`

### Lua Example
`le_calculate_lighting_color_with_normal(pos, normal, out, lightIntensityScalar)`

### Parameters
| Field | Type |
| ----- | ---- |
| pos | [Vec3f](structs.md#Vec3f) |
| normal | [Vec3f](structs.md#Vec3f) |
| out | [Color](structs.md#Color) |
| lightIntensityScalar | `number` |

### Returns
- None

### C Prototype
`void le_calculate_lighting_color_with_normal(Vec3f pos, Vec3f normal, VEC_OUT Color out, f32 lightIntensityScalar);`
