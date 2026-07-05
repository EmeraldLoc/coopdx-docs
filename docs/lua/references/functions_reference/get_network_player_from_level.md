
## [get_network_player_from_level](#get_network_player_from_level)

### Description
Gets the first network player whose information matches `courseNum`, `actNum`, and `levelNum`

### Lua Example
`local networkPlayerValue = get_network_player_from_level(courseNum, actNum, levelNum)`

### Parameters
| Field | Type |
| ----- | ---- |
| courseNum | `integer` |
| actNum | `integer` |
| levelNum | `integer` |

### Returns
- [NetworkPlayer](structs.md#NetworkPlayer)

### C Prototype
`struct NetworkPlayer* get_network_player_from_level(s16 courseNum, s16 actNum, s16 levelNum);`
