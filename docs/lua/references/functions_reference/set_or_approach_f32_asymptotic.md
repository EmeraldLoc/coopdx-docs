
## [set_or_approach_f32_asymptotic](#set_or_approach_f32_asymptotic)

### Description
Smoothly transitions or directly sets a floating-point value (`dst`) to approach a target (`goal`).
Uses asymptotic scaling for gradual adjustments or direct assignment.
Returns FALSE if `dst` reaches `goal`

### Lua Example
`local integerValue, dst = set_or_approach_f32_asymptotic(dst, goal, scale)`

### Parameters
| Field | Type |
| ----- | ---- |
| dst | `number` |
| goal | `number` |
| scale | `number` |

### Returns
- `integer`
- `number`

### C Prototype
`s32 set_or_approach_f32_asymptotic(INOUT f32 *dst, f32 goal, f32 scale);`
