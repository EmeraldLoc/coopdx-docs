
## [begin_braking_action](#begin_braking_action)

### Description
Begins a braking action if Mario's forward velocity is high enough or transitions to a decelerating action otherwise.
Also handles the scenario where Mario is up against a wall, transitioning to a standing state

### Lua Example
`local integerValue = begin_braking_action(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 begin_braking_action(struct MarioState *m);`
