
## [animated_stationary_ground_step](#animated_stationary_ground_step)

### Description
Performs a stationary step, sets `m`'s animation and sets action to `endAction` once the animation finishes

### Lua Example
`animated_stationary_ground_step(m, animation, endAction)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| animation | `integer` |
| endAction | `integer` |

### Returns
- None

### C Prototype
`void animated_stationary_ground_step(struct MarioState *m, s32 animation, u32 endAction);`
