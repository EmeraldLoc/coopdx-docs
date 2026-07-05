
## [arc_to_goal_pos](#arc_to_goal_pos)

### Description
Calculates the time it takes for the current object to follow an arc from `pos` to `goal`

### Lua Example
`local integerValue = arc_to_goal_pos(goal, pos, yVel, gravity)`

### Parameters
| Field | Type |
| ----- | ---- |
| goal | [Vec3f](structs.md#Vec3f) |
| pos | [Vec3f](structs.md#Vec3f) |
| yVel | `number` |
| gravity | `number` |

### Returns
- `integer`

### C Prototype
`s32 arc_to_goal_pos(Vec3f goal, Vec3f pos, f32 yVel, f32 gravity);`
