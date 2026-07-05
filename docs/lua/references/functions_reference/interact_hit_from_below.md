
## [interact_hit_from_below](#interact_hit_from_below)

### Description
Handles interactions where Mario hits an object from below (e.g., hitting a block from underneath). Determines if Mario damages/destroys the object, or if it damages Mario.
Useful for handling upward attacks, hitting coin blocks, or interacting with certain NPCs from below

### Lua Example
`local integerValue = interact_hit_from_below(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_hit_from_below(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
