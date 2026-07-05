
## [apply_landing_accel](#apply_landing_accel)

### Description
Applies friction-like deceleration if the floor is flat, or slope-based acceleration if the floor is sloped.
Capped in such a way that Mario eventually stops or stabilizes on flatter ground

### Lua Example
`local integerValue = apply_landing_accel(m, frictionFactor)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| frictionFactor | `number` |

### Returns
- `integer`

### C Prototype
`s32 apply_landing_accel(struct MarioState *m, f32 frictionFactor);`
