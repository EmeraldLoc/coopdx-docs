
## [should_start_or_continue_dialog](#should_start_or_continue_dialog)

### Description
Checks if the dialog from a specified `object` should start or continue for this particular Mario. Ensures Mario is visible to enemies (i.e., not in certain invulnerable states) and, for remote players, validates the correct dialog object

### Lua Example
`local integerValue = should_start_or_continue_dialog(m, object)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| object | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u8 should_start_or_continue_dialog(struct MarioState* m, struct Object* object);`
