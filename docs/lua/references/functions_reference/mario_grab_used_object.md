
## [mario_grab_used_object](#mario_grab_used_object)

### Description
Grabs the object currently referenced by Mario's `usedObj` if it's not already being held.
Changes the object's state to indicate it is now held by Mario.
Useful for handling the moment Mario successfully picks up an object

### Lua Example
`mario_grab_used_object(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void mario_grab_used_object(struct MarioState *m);`
