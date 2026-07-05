
## [begin_walking_action](#begin_walking_action)

### Description
Sets Mario's facing yaw to his intended yaw, applies a specified forward velocity, and transitions to the given action (e.g., `ACT_WALKING`).

### Lua Example
`local integerValue = begin_walking_action(m, forwardVel, action, actionArg)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| forwardVel | `number` |
| action | `integer` |
| actionArg | `integer` |

### Returns
- `integer`

### C Prototype
`s32 begin_walking_action(struct MarioState *m, f32 forwardVel, u32 action, u32 actionArg);`
