
## [stomach_slide_action](#stomach_slide_action)

### Description
Updates Mario's sliding state where he is on his stomach. Similar to other slide actions but has a chance to roll out if A or B is pressed.
Uses `common_slide_action` for the core movement logic

### Lua Example
`local integerValue = stomach_slide_action(m, stopAction, airAction, animation)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| stopAction | `integer` |
| airAction | `integer` |
| animation | `integer` |

### Returns
- `integer`

### C Prototype
`s32 stomach_slide_action(struct MarioState *m, u32 stopAction, u32 airAction, s32 animation);`
