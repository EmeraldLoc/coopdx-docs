
## [interact_spiny_walking](#interact_spiny_walking)

### Description
Handles interaction with Spiny-walking enemies. If Mario attacks it (e.g., by punching), the enemy is hurt. If he fails to attack properly (say bouncing on top), Mario takes damage and knockback.
Useful for enemies that cannot be stomped from above and require direct attacks

### Lua Example
`local integerValue = interact_spiny_walking(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_spiny_walking(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
