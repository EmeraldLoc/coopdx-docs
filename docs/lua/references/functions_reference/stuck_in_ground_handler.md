
## [stuck_in_ground_handler](#stuck_in_ground_handler)

### Description
Handles the cutscene and animation sequence for when Mario is stuck in the ground (head, butt, or feet). Plays a designated `animation`, checks specific frames (`unstuckFrame`, `target2`, `target3`) for sound effects or transitions, and frees Mario to the `endAction` once the animation completes

### Lua Example
`stuck_in_ground_handler(m, animation, unstuckFrame, target2, target3, endAction)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| animation | `integer` |
| unstuckFrame | `integer` |
| target2 | `integer` |
| target3 | `integer` |
| endAction | `integer` |

### Returns
- None

### C Prototype
`void stuck_in_ground_handler(struct MarioState *m, s32 animation, s32 unstuckFrame, s32 target2, s32 target3, s32 endAction);`
