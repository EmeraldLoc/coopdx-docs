
## [interact_bbh_entrance](#interact_bbh_entrance)

### Description
Handles Mario's interaction with the Boo's Big Haunt (BBH) entrance object. When Mario tries to enter the BBH area, this function determines the resulting action (e.g., a jump or spin entrance)

### Lua Example
`local integerValue = interact_bbh_entrance(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_bbh_entrance(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
