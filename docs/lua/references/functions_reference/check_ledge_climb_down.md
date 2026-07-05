
## [check_ledge_climb_down](#check_ledge_climb_down)

### Description
Checks if Mario is near an edge while moving slowly and the floor below that edge is significantly lower.
If the conditions are met, transitions Mario into a ledge-climb-down action and positions him accordingly on the edge

### Lua Example
`check_ledge_climb_down(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void check_ledge_climb_down(struct MarioState *m);`
