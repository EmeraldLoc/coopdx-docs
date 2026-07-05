
## [spline_get_weights](#spline_get_weights)

### Description
Computes spline interpolation weights for a given parameter `t` and stores these weights in `result`. This is used in spline-based animations to find intermediate positions between keyframes

### Lua Example
`spline_get_weights(m, result, t, c)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| result | [Vec4f](structs.md#Vec4f) |
| t | `number` |
| c | `integer` |

### Returns
- None

### C Prototype
`void spline_get_weights(struct MarioState* m, VEC_OUT Vec4f result, f32 t, UNUSED s32 c);`
