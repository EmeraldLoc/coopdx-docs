
## [check_common_object_cancels](#check_common_object_cancels)

### Description
Checks for and handles common conditions that would cancel Mario's current object action. This includes transitioning
to a water plunge if below the water level, becoming squished if appropriate, or switching to standing death action
if Mario is dead

### Lua Example
`local integerValue = check_common_object_cancels(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 check_common_object_cancels(struct MarioState *m);`
