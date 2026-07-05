
## [play_climbing_sounds](#play_climbing_sounds)

### Description
Plays the appropriate climbing sound effect depending on whether Mario is on a tree or a pole. If `b == 1`, it plays the "climbing up" sound; otherwise, it plays the "sliding down" sound

### Lua Example
`play_climbing_sounds(m, b)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| b | `integer` |

### Returns
- None

### C Prototype
`void play_climbing_sounds(struct MarioState *m, s32 b);`
