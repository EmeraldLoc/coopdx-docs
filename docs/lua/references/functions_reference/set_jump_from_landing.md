
## [set_jump_from_landing](#set_jump_from_landing)

### Description
When Mario lands on the ground, decides whether to jump again (single, double, triple) or enter a steep jump if the floor is very steep. Handles quicksand logic as well

### Lua Example
`local integerValue = set_jump_from_landing(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 set_jump_from_landing(struct MarioState *m);`
