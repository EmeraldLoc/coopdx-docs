
## [interact_mr_blizzard](#interact_mr_blizzard)

### Description
Handles interaction with Mr. Blizzard (the snowman enemy) or similar objects.
If Mario is attacked or collides with Mr. Blizzard, it applies damage and knockback if not protected or attacking

### Lua Example
`local integerValue = interact_mr_blizzard(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_mr_blizzard(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
