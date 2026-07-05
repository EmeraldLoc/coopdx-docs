
## [is_player_active](#is_player_active)

### Description
Checks if `m` is in the current course/act/level/area and isn't bubbled

### Lua Example
`local integerValue = is_player_active(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`u8 is_player_active(struct MarioState* m);`
