
## [update_hang_stationary](#update_hang_stationary)

### Description
Keeps Mario stationary while he is hanging from a ceiling. This function zeroes out his velocity and ensures he remains aligned with the ceiling

### Lua Example
`update_hang_stationary(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void update_hang_stationary(struct MarioState *m);`
