
## [determine_interaction](#determine_interaction)

### Description
Determines how Mario interacts with a given object based on his current action, position, and other state variables.
Calculates the appropriate interaction type (e.g., punch, kick, ground pound) that should result from Mario's contact with the specified object (`o`).
Useful for handling different types of player-object collisions, attacks, and object behaviors

### Lua Example
`local integerValue = determine_interaction(m, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 determine_interaction(struct MarioState *m, struct Object *o);`
