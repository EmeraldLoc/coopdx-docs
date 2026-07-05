
## [is_anim_at_end](#is_anim_at_end)

### Description
Checks if Mario's current animation has reached its final frame (i.e., the last valid frame in the animation).
Useful for deciding when to transition out of an animation-driven action

### Lua Example
`local integerValue = is_anim_at_end(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 is_anim_at_end(struct MarioState *m);`
