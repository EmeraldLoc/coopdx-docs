
## [check_ground_dive_or_punch](#check_ground_dive_or_punch)

### Description
Checks if the B button was pressed to either initiate a dive (if moving fast enough) or a punch (if moving slowly).
Returns `true` if the action was changed to either a dive or a punching attack

### Lua Example
`local integerValue = check_ground_dive_or_punch(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 check_ground_dive_or_punch(struct MarioState *m);`
