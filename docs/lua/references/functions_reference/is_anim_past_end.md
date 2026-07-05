
## [is_anim_past_end](#is_anim_past_end)

### Description
Checks if Mario's current animation has passed the second-to-last valid frame (i.e., effectively at or beyond its final frames).
Useful for advanced checks where slightly early transitions or timing are needed before the final frame

### Lua Example
`local integerValue = is_anim_past_end(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 is_anim_past_end(struct MarioState *m);`
