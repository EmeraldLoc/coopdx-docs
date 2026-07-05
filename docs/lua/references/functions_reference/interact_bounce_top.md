
## [interact_bounce_top](#interact_bounce_top)

### Description
Handles interactions where Mario bounces off the top of an object (e.g., Goombas, Koopas).
Checks if Mario attacks the object from above and applies the appropriate knockback, sound effects, and object state changes.
Useful for enemy defeat mechanics and platform bouncing

### Lua Example
`local integerValue = interact_bounce_top(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_bounce_top(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
