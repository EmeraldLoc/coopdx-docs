
## [interact_text](#interact_text)

### Description
Handles interaction with signs, NPCs, and other text-bearing objects. If Mario presses the interact button facing them, he enters a dialog reading state.
Useful for managing hints, story elements, or gameplay instructions through in-game dialogue

### Lua Example
`local integerValue = interact_text(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_text(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
