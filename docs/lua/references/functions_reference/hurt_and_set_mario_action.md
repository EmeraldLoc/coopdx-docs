
## [hurt_and_set_mario_action](#hurt_and_set_mario_action)

### Description
Increments Mario's `hurtCounter` and immediately sets a new action. Often used when Mario takes damage and transitions into a knockback or stunned action.

### Lua Example
`local integerValue = hurt_and_set_mario_action(m, action, actionArg, hurtCounter)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| action | `integer` |
| actionArg | `integer` |
| hurtCounter | `integer` |

### Returns
- `integer`

### C Prototype
`s32 hurt_and_set_mario_action(struct MarioState *m, u32 action, u32 actionArg, s16 hurtCounter);`
