
## [mario_retrieve_cap](#mario_retrieve_cap)

### Description
Retrieves Mario's normal cap if it was previously lost.
Removes the cap from Mario's hand state and places it on his head.
Useful when Mario recovers his normal cap from enemies, finds it in a level, or if it were to disappear

### Lua Example
`mario_retrieve_cap(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void mario_retrieve_cap(struct MarioState* m);`
