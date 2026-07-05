
## [perform_hanging_step](#perform_hanging_step)

### Description
Performs a single step of movement while Mario is hanging from a ceiling. It handles wall collisions and checks the floor and ceiling to determine if Mario remains hanging, leaves the ceiling, or hits it

### Lua Example
`local integerValue = perform_hanging_step(m, nextPos)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| nextPos | [Vec3f](structs.md#Vec3f) |

### Returns
- `integer`

### C Prototype
`s32 perform_hanging_step(struct MarioState *m, VEC_OUT Vec3f nextPos);`
