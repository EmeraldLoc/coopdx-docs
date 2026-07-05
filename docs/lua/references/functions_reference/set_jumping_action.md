
## [set_jumping_action](#set_jumping_action)

### Description
Sets Mario to a jumping action (regular, double, triple, or steep jump) if conditions allow it. If the floor is too steep or if in quicksand, it changes the action accordingly

### Lua Example
`local integerValue = set_jumping_action(m, action, actionArg)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| action | `integer` |
| actionArg | `integer` |

### Returns
- `integer`

### C Prototype
`s32 set_jumping_action(struct MarioState *m, u32 action, u32 actionArg);`
