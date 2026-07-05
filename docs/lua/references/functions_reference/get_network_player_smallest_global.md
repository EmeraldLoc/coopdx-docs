
## [get_network_player_smallest_global](#get_network_player_smallest_global)

### Description
Gets the active network player with the smallest global index. Useful for assigning one player to "own" some kind of functionality or object

### Lua Example
`local networkPlayerValue = get_network_player_smallest_global()`

### Parameters
- None

### Returns
- [NetworkPlayer](structs.md#NetworkPlayer)

### C Prototype
`struct NetworkPlayer* get_network_player_smallest_global(void);`
