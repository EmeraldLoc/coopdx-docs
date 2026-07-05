
## [mario_bonk_reflection](#mario_bonk_reflection)

### Description
Reflects Mario off a wall if he is colliding with one and flips forward velocity if `negateSpeed` is TRUE

### Lua Example
`mario_bonk_reflection(m, negateSpeed)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| negateSpeed | `integer` |

### Returns
- None

### C Prototype
`void mario_bonk_reflection(struct MarioState *m, u8 negateSpeed);`
