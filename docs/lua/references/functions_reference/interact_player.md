
## [interact_player](#interact_player)

### Description
Handles interaction with another player (in multiplayer scenarios).
Checks if Mario and another player collide and resolves any special behavior like bouncing on top.
Useful for multiplayer interactions, such as PvP or cooperative gameplay mechanics

### Lua Example
`local integerValue = interact_player(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_player(struct MarioState* m, UNUSED u32 interactType, struct Object* o);`
