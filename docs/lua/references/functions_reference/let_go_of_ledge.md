
## [let_go_of_ledge](#let_go_of_ledge)

### Description
Handles Mario letting go of a ledge by adjusting his position and setting his velocity to make him fall away from the ledge. The action then transitions to a 'soft bonk' state

### Lua Example
`local integerValue = let_go_of_ledge(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 let_go_of_ledge(struct MarioState *m);`
