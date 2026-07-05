
## [general_star_dance_handler](#general_star_dance_handler)

### Description
Manages the star collection dance sequence for Mario, both on land and in water. Plays music, spawns the celebration star, increments the star count, and triggers level exits or dialogs at the correct times

### Lua Example
`general_star_dance_handler(m, isInWater)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| isInWater | `integer` |

### Returns
- None

### C Prototype
`void general_star_dance_handler(struct MarioState *m, s32 isInWater);`
