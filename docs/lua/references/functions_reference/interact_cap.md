
## [interact_cap](#interact_cap)

### Description
Handles interaction when Mario picks up a cap object. This includes normal caps, wing caps, vanish caps, and metal caps.
Updates Mario's state (e.g., cap timers, sound effects) and may initiate putting on the cap animation.
Useful for managing cap statuses

### Lua Example
`local integerValue = interact_cap(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_cap(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
