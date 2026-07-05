
## [interact_snufit_bullet](#interact_snufit_bullet)

### Description
Handles interaction with Snufit bullets (projectiles fired by certain enemies). If Mario is not protected, he takes damage. Otherwise, the bullet can be destroyed

### Lua Example
`local integerValue = interact_snufit_bullet(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_snufit_bullet(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
