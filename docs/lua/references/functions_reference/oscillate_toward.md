
## [oscillate_toward](#oscillate_toward)

### Description
Oscillates `value` towards `target`. Returns TRUE when `value` reaches `target`

### Lua Example
`local integerValue, value, vel = oscillate_toward(value, vel, target, velCloseToZero, accel, slowdown)`

### Parameters
| Field | Type |
| ----- | ---- |
| value | `integer` |
| vel | `number` |
| target | `integer` |
| velCloseToZero | `number` |
| accel | `number` |
| slowdown | `number` |

### Returns
- `integer`
- `integer`
- `number`

### C Prototype
`s32 oscillate_toward(INOUT s32 *value, INOUT f32 *vel, s32 target, f32 velCloseToZero, f32 accel, f32 slowdown);`
