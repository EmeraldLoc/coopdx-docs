
## [tilt_body_running](#tilt_body_running)

### Description
Tilts Mario's body according to his running speed and slope angle.
Calculates a pitch offset used while running to simulate leaning forward at higher speeds or on slopes

### Lua Example
`local integerValue = tilt_body_running(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s16 tilt_body_running(struct MarioState *m);`
