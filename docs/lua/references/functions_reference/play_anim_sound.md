
## [play_anim_sound](#play_anim_sound)

### Description
Plays a `sound` if Mario's action state and animation frame match the parameters

### Lua Example
`play_anim_sound(m, actionState, animFrame, sound)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| actionState | `integer` |
| animFrame | `integer` |
| sound | `integer` |

### Returns
- None

### C Prototype
`void play_anim_sound(struct MarioState *m, u32 actionState, s32 animFrame, u32 sound);`
