
## [quicksand_jump_land_action](#quicksand_jump_land_action)

### Description
Handles a special landing in quicksand after a jump. Over several frames, Mario emerges from the quicksand.
First part of the animation reduces his quicksand depth. Ends with a normal landing action or transitions back to air if he leaves the ground

### Lua Example
`local integerValue = quicksand_jump_land_action(m, animation1, animation2, endAction, airAction)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| animation1 | `integer` |
| animation2 | `integer` |
| endAction | `integer` |
| airAction | `integer` |

### Returns
- `integer`

### C Prototype
`s32 quicksand_jump_land_action(struct MarioState *m, s32 animation1, s32 animation2, u32 endAction, u32 airAction);`
