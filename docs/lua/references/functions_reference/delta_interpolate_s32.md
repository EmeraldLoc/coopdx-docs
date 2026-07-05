
## [delta_interpolate_s32](#delta_interpolate_s32)

### Description
Linearly interpolates between `a` and `b` with `delta`

### Lua Example
`local integerValue = delta_interpolate_s32(a, b, delta)`

### Parameters
| Field | Type |
| ----- | ---- |
| a | `integer` |
| b | `integer` |
| delta | `number` |

### Returns
- `integer`

### C Prototype
`s32 delta_interpolate_s32(s32 a, s32 b, f32 delta);`
