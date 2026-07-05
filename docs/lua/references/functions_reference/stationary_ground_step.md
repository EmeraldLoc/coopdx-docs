
## [stationary_ground_step](#stationary_ground_step)

### Description
Performs a full Mario stationary physics step (4 substeps) and returns a `GROUND_STEP_*` result

### Lua Example
`local integerValue = stationary_ground_step(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 stationary_ground_step(struct MarioState *m);`
