
## [update_ledge_climb_camera](#update_ledge_climb_camera)

### Description
Gradually adjusts the camera position to track Mario as he climbs a ledge. This creates a smoother view transition from the ledge-grab camera angle to Mario's new location on top of the ledge

### Lua Example
`update_ledge_climb_camera(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void update_ledge_climb_camera(struct MarioState *m);`
