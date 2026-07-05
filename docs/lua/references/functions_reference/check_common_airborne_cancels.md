
## [check_common_airborne_cancels](#check_common_airborne_cancels)

### Description
Checks for and handles common conditions that would cancel Mario's current air action. This includes transitioning
to a water plunge if below the water level, becoming squished if appropriate, or switching to vertical wind action
if on certain wind surfaces. Also resets `m.quicksandDepth`

### Lua Example
`local integerValue = check_common_airborne_cancels(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 check_common_airborne_cancels(struct MarioState *m);`
