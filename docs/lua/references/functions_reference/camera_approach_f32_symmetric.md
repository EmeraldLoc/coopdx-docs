
## [camera_approach_f32_symmetric](#camera_approach_f32_symmetric)

### Description
Symmetrically approaches a floating-point value (`target`) with a fixed increment (`increment`) per frame.
Limits the rate of change to ensure gradual transitions

### Lua Example
`local numberValue = camera_approach_f32_symmetric(value, target, increment)`

### Parameters
| Field | Type |
| ----- | ---- |
| value | `number` |
| target | `number` |
| increment | `number` |

### Returns
- `number`

### C Prototype
`f32 camera_approach_f32_symmetric(f32 value, f32 target, f32 increment);`
