
## [common_air_action_step](#common_air_action_step)

### Description
Performs a standard step update for air actions without knockback, typically used for jumps or freefalls.
Updates Mario's velocity (and possibly checks horizontal wind), then calls `perform_air_step` with given `stepArg`.
Handles how Mario lands, hits walls, grabs ledges, or grabs ceilings. Optionally sets an animation

### Lua Example
`local integerValue = common_air_action_step(m, landAction, animation, stepArg)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| landAction | `integer` |
| animation | `integer` |
| stepArg | `integer` |

### Returns
- `integer`

### C Prototype
`u32 common_air_action_step(struct MarioState *m, u32 landAction, s32 animation, u32 stepArg);`
