
## [interact_warp](#interact_warp)

### Description
Handles interaction with warps, including warp pipes and hole warps. If Mario steps onto a warp, he either transitions into another area or level.
Useful for connecting different parts of the game world and controlling transitions between levels as well as custom warp areas

### Lua Example
`local integerValue = interact_warp(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_warp(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
