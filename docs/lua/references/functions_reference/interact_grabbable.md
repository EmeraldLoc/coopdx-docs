
## [interact_grabbable](#interact_grabbable)

### Description
Handles interaction with grabbable objects (e.g., crates, small enemies, or Bowser). Checks if Mario can pick up the object and initiates the grab action if possible.
Useful for course mechanics, throwing items, and Bowser

### Lua Example
`local integerValue = interact_grabbable(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_grabbable(struct MarioState *m, u32 interactType, struct Object *o);`
