
## [init_single_mario](#init_single_mario)

### Description
Initializes the fields of a single `MarioState` structure when the player spawns or respawns. Sets starting position, velocity, action, and various internal flags

### Lua Example
`init_single_mario(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void init_single_mario(struct MarioState* m);`
