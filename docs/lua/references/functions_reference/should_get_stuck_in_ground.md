
## [should_get_stuck_in_ground](#should_get_stuck_in_ground)

### Description
Determines whether Mario should become stuck in the ground after landing, specifically for soft terrain such as snow
or sand, provided certain conditions are met (height of the fall, normal of the floor, etc.).
Returns true if Mario should be stuck, false otherwise

### Lua Example
`local integerValue = should_get_stuck_in_ground(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 should_get_stuck_in_ground(struct MarioState *m);`
