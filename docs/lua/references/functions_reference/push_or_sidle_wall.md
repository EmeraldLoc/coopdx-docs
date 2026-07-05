
## [push_or_sidle_wall](#push_or_sidle_wall)

### Description
When Mario hits a wall during movement, decides whether he's pushing against the wall or sidling along it. Plays pushing animations and sounds if he's head-on, sidles along the wall if he's more angled

### Lua Example
`push_or_sidle_wall(m, startPos)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| startPos | [Vec3f](structs.md#Vec3f) |

### Returns
- None

### C Prototype
`void push_or_sidle_wall(struct MarioState *m, Vec3f startPos);`
