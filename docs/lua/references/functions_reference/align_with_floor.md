
## [align_with_floor](#align_with_floor)

### Description
Aligns Mario's position and model transformation matrix to match the floor's angle. Specifically: Sets Mario's vertical position to be at `m.floorHeight` plus any active character animation offset and adjusts Mario's `throwMatrix` so that his body appears flush with the floor

### Lua Example
`align_with_floor(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void align_with_floor(struct MarioState *m);`
