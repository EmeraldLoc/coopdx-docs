
## [perform_ground_step](#perform_ground_step)

### Description
Performs a full Mario ground physics step (4 substeps) and returns a `GROUND_STEP_*` result

### Lua Example
`local integerValue = perform_ground_step(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 perform_ground_step(struct MarioState *m);`
