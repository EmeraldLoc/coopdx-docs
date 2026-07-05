
## [sins](#sins)

### Description
Calculates the sine of the given angle, where the angle is specified as a signed 16-bit integer representing a fixed-point "SM64 angle". This function returns a floating-point result corresponding to sin(angle)

### Lua Example
`local numberValue = sins(sm64Angle)`

### Parameters
| Field | Type |
| ----- | ---- |
| sm64Angle | `integer` |

### Returns
- `number`

### C Prototype
`f32 sins(s16 sm64Angle);`
