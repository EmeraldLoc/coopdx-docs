
## [update_lava_boost_or_twirling](#update_lava_boost_or_twirling)

### Description
Updates Mario's movement when in actions like lava boost or twirling in mid-air. Applies player input to adjust forward velocity
and facing angle, but in a more restricted manner compared to standard jump movement. Used by `ACT_LAVA_BOOST` and `ACT_TWIRLING`

### Lua Example
`update_lava_boost_or_twirling(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void update_lava_boost_or_twirling(struct MarioState *m);`
