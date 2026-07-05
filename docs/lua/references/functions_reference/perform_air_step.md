
## [perform_air_step](#perform_air_step)

### Description
Performs a full Mario air physics step (4 substeps) and returns an `AIR_STEP_*` result

### Lua Example
`local integerValue = perform_air_step(m, stepArg)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| stepArg | `integer` |

### Returns
- `integer`

### C Prototype
`s32 perform_air_step(struct MarioState *m, u32 stepArg);`
