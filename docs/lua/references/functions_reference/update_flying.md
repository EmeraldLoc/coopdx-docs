
## [update_flying](#update_flying)

### Description
Handles the complete flying logic for Mario (usually with the wing cap). Continuously updates pitch and yaw based on controller input,
applies drag, and adjusts forward velocity. Also updates Mario's model angles for flight animations

### Lua Example
`update_flying(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void update_flying(struct MarioState *m);`
