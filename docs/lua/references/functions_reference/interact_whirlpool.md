
## [interact_whirlpool](#interact_whirlpool)

### Description
Handles interaction with whirlpools. If Mario gets caught in a whirlpool, he's pulled toward it, resulting in a unique "caught" action.
Useful for hazards that trap Mario like whirlpools

### Lua Example
`local integerValue = interact_whirlpool(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_whirlpool(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
