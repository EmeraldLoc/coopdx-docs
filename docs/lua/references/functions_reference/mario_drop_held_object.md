
## [mario_drop_held_object](#mario_drop_held_object)

### Description
Causes Mario to drop the object he is currently holding. Sets the held object's state accordingly and places it in front of Mario.
Useful for releasing carried objects, such as throwing Bob-ombs or setting down crates

### Lua Example
`mario_drop_held_object(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void mario_drop_held_object(struct MarioState *m);`
