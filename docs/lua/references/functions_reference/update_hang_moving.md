
## [update_hang_moving](#update_hang_moving)

### Description
Updates Mario's velocity and position while he is moving across a hangable ceiling. It calls `perform_hanging_step()` to handle collisions and movement logic, returning a status code indicating if Mario is still hanging or if he left the ceiling

### Lua Example
`local integerValue = update_hang_moving(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 update_hang_moving(struct MarioState *m);`
