
## [mario_execute_cutscene_action](#mario_execute_cutscene_action)

### Description
Executes Mario's current cutscene action based on his `action` field. Includes various story-related sequences like entering doors, collecting stars, and final boss cutscenes. Delegates to the appropriate function for each cutscene action

### Lua Example
`local integerValue = mario_execute_cutscene_action(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 mario_execute_cutscene_action(struct MarioState *m);`
