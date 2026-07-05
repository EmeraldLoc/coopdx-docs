
## [get_network_player_from_area](#get_network_player_from_area)

### Description
Gets the first network player whose information matches `courseNum`, `actNum`, `levelNum`, and `areaIndex`

### Lua Example
`local networkPlayerValue = get_network_player_from_area(courseNum, actNum, levelNum, areaIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| courseNum | `integer` |
| actNum | `integer` |
| levelNum | `integer` |
| areaIndex | `integer` |

### Returns
- [NetworkPlayer](structs.md#NetworkPlayer)

### C Prototype
`struct NetworkPlayer* get_network_player_from_area(s16 courseNum, s16 actNum, s16 levelNum, s16 areaIndex);`
