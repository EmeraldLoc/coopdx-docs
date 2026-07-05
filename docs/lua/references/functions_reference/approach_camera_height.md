
## [approach_camera_height](#approach_camera_height)

### Description
Adjusts the camera's height toward a target value (`goalHeight`) while respecting terrain and obstructions.
This is really wonky and probably shouldn't be used, prefer `gLakituStates`

### Lua Example
`approach_camera_height(c, goal, inc)`

### Parameters
| Field | Type |
| ----- | ---- |
| c | [Camera](structs.md#Camera) |
| goal | `number` |
| inc | `number` |

### Returns
- None

### C Prototype
`void approach_camera_height(struct Camera *c, f32 goal, f32 inc);`
