
## [common_death_handler](#common_death_handler)

### Description
Handles shared logic for Mario's various death states. Plays the specified death animation (`animation`), checks for a specific frame (`frameToDeathWarp`) to trigger a warp or bubble state if allowed, and sets Mario's eye state to 'dead'

### Lua Example
`local integerValue = common_death_handler(m, animation, frameToDeathWarp)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| animation | `integer` |
| frameToDeathWarp | `integer` |

### Returns
- `integer`

### C Prototype
`s32 common_death_handler(struct MarioState *m, s32 animation, s32 frameToDeathWarp);`
