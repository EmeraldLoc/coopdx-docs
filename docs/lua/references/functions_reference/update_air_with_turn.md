
## [update_air_with_turn](#update_air_with_turn)

### Description
Updates Mario's air movement while allowing him to turn. Checks horizontal wind and applies a moderate amount of drag,
approaches the forward velocity toward zero if no input is pressed, and modifies forward velocity/angle based on stick input

### Lua Example
`update_air_with_turn(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void update_air_with_turn(struct MarioState *m);`
