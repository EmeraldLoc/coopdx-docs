
## [atan2s](#atan2s)

### Description
Computes the arctangent of y/x and returns the angle as a signed 16-bit integer, typically representing a direction in the SM64 fixed-point angle format. This can be used to find an angle between x and y coordinates

### Lua Example
`local integerValue = atan2s(y, x)`

### Parameters
| Field | Type |
| ----- | ---- |
| y | `number` |
| x | `number` |

### Returns
- `integer`

### C Prototype
`s16 atan2s(f32 y, f32 x);`
