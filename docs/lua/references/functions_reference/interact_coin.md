
## [interact_coin](#interact_coin)

### Description
Handles Mario's interaction with coins. Collecting a coin increases Mario's coin count and heals him slightly.
Useful for score, and coin management

### Lua Example
`local integerValue = interact_coin(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_coin(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
