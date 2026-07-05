
## [mario_floor_is_slippery](#mario_floor_is_slippery)

### Description
Checks whether Mario's current floor is slippery based on both the floor's surface class and Mario's environment (e.g., special slides).
Useful for deciding if Mario should transition to sliding or maintain normal traction

### Lua Example
`local integerValue = mario_floor_is_slippery(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`u32 mario_floor_is_slippery(struct MarioState *m);`
