
## [common_slide_action_with_jump](#common_slide_action_with_jump)

### Description
Builds on `common_slide_action` by also allowing Mario to jump out of a slide if A is pressed after a short delay.
If the sliding slows enough, Mario transitions to a specified stopping action

### Lua Example
`local integerValue = common_slide_action_with_jump(m, stopAction, jumpAction, airAction, animation)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| stopAction | `integer` |
| jumpAction | `integer` |
| airAction | `integer` |
| animation | `integer` |

### Returns
- `integer`

### C Prototype
`s32 common_slide_action_with_jump(struct MarioState *m, u32 stopAction, u32 jumpAction, u32 airAction, s32 animation);`
