
## [interact_clam_or_bubba](#interact_clam_or_bubba)

### Description
Handles interactions with objects like Clams or Bubbas, which can damage Mario or, in Bubba's case, eat Mario.
If Bubba eats Mario, it triggers a unique "caught" action. Otherwise, it deals damage and knockback if hit by a Clam

### Lua Example
`local integerValue = interact_clam_or_bubba(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_clam_or_bubba(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
