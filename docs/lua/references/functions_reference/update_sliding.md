
## [update_sliding](#update_sliding)

### Description
Updates Mario's sliding state each frame, applying additional friction or acceleration based on the surface's slipperiness.
Also checks if speed has slowed below a threshold to end the slide.
Returns `true` if sliding has stopped

### Lua Example
`local integerValue = update_sliding(m, stopSpeed)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| stopSpeed | `number` |

### Returns
- `integer`

### C Prototype
`s32 update_sliding(struct MarioState *m, f32 stopSpeed);`
