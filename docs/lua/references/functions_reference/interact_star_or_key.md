
## [interact_star_or_key](#interact_star_or_key)

### Description
Handles interaction with Stars or Keys. If Mario collects a star or key, it triggers a specific star grab cutscene and progression is updated. Also handles no-exit variants (like the wing cap stage star).
Useful for the main progression system of collecting Stars and unlocking new areas

### Lua Example
`local integerValue = interact_star_or_key(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_star_or_key(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
