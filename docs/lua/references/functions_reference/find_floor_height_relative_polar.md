
## [find_floor_height_relative_polar](#find_floor_height_relative_polar)

### Description
Finds the floor height relative to Mario's current position given a polar displacement (`angleFromMario`, `distFromMario`).
Useful for determining height differentials ahead or behind Mario, e.g. for slope checks or collision logic

### Lua Example
`local numberValue = find_floor_height_relative_polar(m, angleFromMario, distFromMario)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| angleFromMario | `integer` |
| distFromMario | `number` |

### Returns
- `number`

### C Prototype
`f32 find_floor_height_relative_polar(struct MarioState *m, s16 angleFromMario, f32 distFromMario);`
