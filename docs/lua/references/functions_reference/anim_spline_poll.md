
## [anim_spline_poll](#anim_spline_poll)

### Description
Advances the spline-based animation associated with `m` and stores the current interpolated position in `result`. It returns the animation's status, allowing the caller to determine if the animation is ongoing or has completed

### Lua Example
`local integerValue = anim_spline_poll(m, result)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| result | [Vec3f](structs.md#Vec3f) |

### Returns
- `integer`

### C Prototype
`s32 anim_spline_poll(struct MarioState* m, VEC_OUT Vec3f result);`
