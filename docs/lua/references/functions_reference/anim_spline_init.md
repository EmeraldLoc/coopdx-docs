
## [anim_spline_init](#anim_spline_init)

### Description
Initializes a spline-based animation for the `MarioState` structure `m` using the provided array of 3D signed-integer vectors `keyFrames`. This sets up the animation so that it can be advanced by polling

### Lua Example
`anim_spline_init(m, keyFrames)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| keyFrames | `Pointer` <`Vec4s`> |

### Returns
- None

### C Prototype
`void anim_spline_init(struct MarioState* m, Vec4s *keyFrames);`
