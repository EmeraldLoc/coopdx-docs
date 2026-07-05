
## [interact_bully](#interact_bully)

### Description
Handles interaction with Bully enemies. Determines if Mario attacks the Bully or gets knocked back. Updates Mario's velocity and state accordingly, and can defeat the Bully if attacked successfully.
Useful for enemy encounters that involve pushing and shoving mechanics rather than just stomping like the bullies

### Lua Example
`local integerValue = interact_bully(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_bully(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
