
## [analog_stick_held_back](#analog_stick_held_back)

### Description
Checks if the analog stick is held significantly behind Mario's current facing angle.
Returns true if the stick is far enough in the opposite direction, indicating Mario wants to move backward

### Lua Example
`local integerValue = analog_stick_held_back(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 analog_stick_held_back(struct MarioState *m);`
