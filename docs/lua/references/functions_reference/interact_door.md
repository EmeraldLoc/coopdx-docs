
## [interact_door](#interact_door)

### Description
Handles interaction when Mario touches a door. If Mario meets the star requirement or has the key, he can unlock/open the door. Otherwise, it may display dialog indicating the requirement.
Useful for controlling access to locked areas and providing progression gating in the game

### Lua Example
`local integerValue = interact_door(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_door(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
