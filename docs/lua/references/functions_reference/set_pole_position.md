
## [set_pole_position](#set_pole_position)

### Description
Sets Mario's position and alignment while he is on a climbable pole or tree. This function checks collisions with floors and ceilings, and updates Mario's action if he leaves the pole or touches the floor.
Useful for ensuring Mario's correct placement and transitions when climbing poles or trees

### Lua Example
`local integerValue = set_pole_position(m, offsetY)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| offsetY | `number` |

### Returns
- `integer`

### C Prototype
`s32 set_pole_position(struct MarioState *m, f32 offsetY);`
