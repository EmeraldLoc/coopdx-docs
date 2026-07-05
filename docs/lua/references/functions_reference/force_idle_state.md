
## [force_idle_state](#force_idle_state)

### Description
Forces Mario into an idle state, either `ACT_IDLE` or `ACT_WATER_IDLE` depending on whether he is submerged.
Useful for quickly resetting Mario's state to an idle pose under special conditions (e.g., cutscene triggers)

### Lua Example
`local integerValue = force_idle_state(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 force_idle_state(struct MarioState* m);`
