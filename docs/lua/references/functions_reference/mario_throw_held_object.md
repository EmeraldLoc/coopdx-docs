
## [mario_throw_held_object](#mario_throw_held_object)

### Description
Throws the object Mario is currently holding. The object is placed in front of Mario and given a forward velocity.
Useful for attacking enemies with thrown objects, solving puzzles by throwing crates, or interacting with environment items

### Lua Example
`mario_throw_held_object(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void mario_throw_held_object(struct MarioState *m);`
