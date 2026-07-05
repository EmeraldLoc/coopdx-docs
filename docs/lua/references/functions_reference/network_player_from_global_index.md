
## [network_player_from_global_index](#network_player_from_global_index)

### Description
Gets a network player from `globalIndex`

### Lua Example
`local networkPlayerValue = network_player_from_global_index(globalIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| globalIndex | `integer` |

### Returns
- [NetworkPlayer](structs.md#NetworkPlayer)

### C Prototype
`struct NetworkPlayer* network_player_from_global_index(u8 globalIndex);`
