
## [lava_boost_on_wall](#lava_boost_on_wall)

### Description
Allows Mario to 'lava boost' off a lava wall, reorienting him to face away from the wall and adjusting forward velocity.
Increases Mario's hurt counter if he's not metal, plays a burning sound, and transitions his action to `ACT_LAVA_BOOST`.
Useful for handling collisions with lava walls, giving Mario a strong upward/forward boost at the cost of health

### Lua Example
`local integerValue = lava_boost_on_wall(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 lava_boost_on_wall(struct MarioState *m);`
