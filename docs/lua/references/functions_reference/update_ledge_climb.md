
## [update_ledge_climb](#update_ledge_climb)

### Description
Updates Mario's climb onto a ledge by setting the chosen climbing animation and transitioning to the specified end action (e.g., standing idle) once the animation finishes. If the end action is `ACT_IDLE`, Mario is placed on top of the ledge

### Lua Example
`update_ledge_climb(m, animation, endAction)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| animation | `integer` |
| endAction | `integer` |

### Returns
- None

### C Prototype
`void update_ledge_climb(struct MarioState *m, s32 animation, u32 endAction);`
