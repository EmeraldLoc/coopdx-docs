
## [set_triple_jump_action](#set_triple_jump_action)

### Description
Determines the proper triple jump action based on Mario's forward velocity and the Wing Cap flag: Normal triple jump, flying triple jump, or just a single jump if not enough speed

### Lua Example
`local integerValue = set_triple_jump_action(m, action, actionArg)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| action | `integer` |
| actionArg | `integer` |

### Returns
- `integer`

### C Prototype
`s32 set_triple_jump_action(struct MarioState *m, UNUSED u32 action, UNUSED u32 actionArg);`
