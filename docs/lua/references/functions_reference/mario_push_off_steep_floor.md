
## [mario_push_off_steep_floor](#mario_push_off_steep_floor)

### Description
Pushes Mario off a steep floor and sets his action to `action` with `actionArg`

### Lua Example
`local integerValue = mario_push_off_steep_floor(m, action, actionArg)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| action | `integer` |
| actionArg | `integer` |

### Returns
- `integer`

### C Prototype
`u32 mario_push_off_steep_floor(struct MarioState *m, u32 action, u32 actionArg);`
