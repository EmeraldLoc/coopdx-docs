
## [check_fall_damage_or_get_stuck](#check_fall_damage_or_get_stuck)

### Description
Checks if Mario should get stuck in the ground after a large fall onto soft terrain (like snow or sand) or if he
should just proceed with regular fall damage calculations. If the terrain and height conditions are met, Mario's
action changes to being stuck in the ground. Otherwise, normal fall damage logic applies

### Lua Example
`local integerValue = check_fall_damage_or_get_stuck(m, hardFallAction)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| hardFallAction | `integer` |

### Returns
- `integer`

### C Prototype
`s32 check_fall_damage_or_get_stuck(struct MarioState *m, u32 hardFallAction);`
