
## [mario_stop_riding_object](#mario_stop_riding_object)

### Description
Stops Mario from riding any currently ridden object (e.g., a Koopa shell or Hoot), updating the object's interaction status and Mario's state.
Useful for cleanly dismounting ridden objects

### Lua Example
`mario_stop_riding_object(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void mario_stop_riding_object(struct MarioState *m);`
