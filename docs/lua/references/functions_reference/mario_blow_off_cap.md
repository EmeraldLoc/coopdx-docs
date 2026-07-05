
## [mario_blow_off_cap](#mario_blow_off_cap)

### Description
Makes Mario blow off his normal cap at a given speed.
Removes the normal cap from Mario's head and spawns it as a collectible object in the game world.
Useful for simulating events where Mario loses his cap due to enemy attacks or environmental forces

### Lua Example
`mario_blow_off_cap(m, capSpeed)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| capSpeed | `number` |

### Returns
- None

### C Prototype
`void mario_blow_off_cap(struct MarioState *m, f32 capSpeed);`
