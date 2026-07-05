
## [interact_koopa_shell](#interact_koopa_shell)

### Description
Handles interaction when Mario touches a Koopa Shell. If conditions are met, Mario can hop onto the shell and start riding it, changing his movement mechanics.
Useful for implementing Koopa Shell behavior

### Lua Example
`local integerValue = interact_koopa_shell(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_koopa_shell(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
