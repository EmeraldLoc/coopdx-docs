
## [approach_s32](#approach_s32)

### Description
Gradually moves an integer `current` value toward a `target` value, increasing it by `inc` if it is too low, or decreasing it by `dec` if it is too high. This is often used for smooth transitions or animations

### Lua Example
`local integerValue = approach_s32(current, target, inc, dec)`

### Parameters
| Field | Type |
| ----- | ---- |
| current | `integer` |
| target | `integer` |
| inc | `integer` |
| dec | `integer` |

### Returns
- `integer`

### C Prototype
`s32 approach_s32(s32 current, s32 target, s32 inc, s32 dec);`
