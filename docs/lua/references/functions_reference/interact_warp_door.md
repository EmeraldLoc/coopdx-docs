
## [interact_warp_door](#interact_warp_door)

### Description
Handles interaction with warp doors that lead to other areas or require keys. If Mario can open the door (has enough stars or a key), he proceeds. Otherwise, it may show a dialog.
Useful for restricting access to certain areas based on progression

### Lua Example
`local integerValue = interact_warp_door(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_warp_door(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
