
## [is_anim_past_frame](#is_anim_past_frame)

### Description
Checks if Mario's current animation is past a specified `animFrame`.
Useful for conditional logic where an action can branch after reaching a specific point in the animation

### Lua Example
`local integerValue = is_anim_past_frame(m, animFrame)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| animFrame | `integer` |

### Returns
- `integer`

### C Prototype
`s32 is_anim_past_frame(struct MarioState *m, s16 animFrame);`
