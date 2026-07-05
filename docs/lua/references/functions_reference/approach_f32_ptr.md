
## [approach_f32_ptr](#approach_f32_ptr)

### Description
Approaches a `target` for `px` using `delta`. Returns TRUE if `px` reaches `target`

### Lua Example
`local integerValue, px = approach_f32_ptr(px, target, delta)`

### Parameters
| Field | Type |
| ----- | ---- |
| px | `number` |
| target | `number` |
| delta | `number` |

### Returns
- `integer`
- `number`

### C Prototype
`s32 approach_f32_ptr(INOUT f32 *px, f32 target, f32 delta);`
