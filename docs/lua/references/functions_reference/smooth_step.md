
## [smooth_step](#smooth_step)

### Description
Smoothly steps between `edge0` and `edge1` with `x` as delta

### Lua Example
`local numberValue = smooth_step(edge0, edge1, x)`

### Parameters
| Field | Type |
| ----- | ---- |
| edge0 | `number` |
| edge1 | `number` |
| x | `number` |

### Returns
- `number`

### C Prototype
`float smooth_step(float edge0, float edge1, float x);`
