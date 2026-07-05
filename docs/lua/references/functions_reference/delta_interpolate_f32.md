
## [delta_interpolate_f32](#delta_interpolate_f32)

### Description
Linearly interpolates between `a` and `b` with `delta`

### Lua Example
`local numberValue = delta_interpolate_f32(a, b, delta)`

### Parameters
| Field | Type |
| ----- | ---- |
| a | `number` |
| b | `number` |
| delta | `number` |

### Returns
- `number`

### C Prototype
`f32 delta_interpolate_f32(f32 a, f32 b, f32 delta);`
