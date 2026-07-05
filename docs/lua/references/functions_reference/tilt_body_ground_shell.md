
## [tilt_body_ground_shell](#tilt_body_ground_shell)

### Description
Tilts Mario's torso and head while riding a shell on the ground to reflect turning.
Similar to other tilt functions but tuned for shell-riding speeds and angles

### Lua Example
`tilt_body_ground_shell(m, startYaw)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| startYaw | `integer` |

### Returns
- None

### C Prototype
`void tilt_body_ground_shell(struct MarioState *m, s16 startYaw);`
