
## [update_walking_speed](#update_walking_speed)

### Description
Updates Mario's walking speed based on player input and floor conditions (e.g., a slow floor or quicksand).
Caps speed at a certain value and may reduce it slightly on steep slopes

### Lua Example
`update_walking_speed(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void update_walking_speed(struct MarioState *m);`
