
## [network_discord_id_from_local_index](#network_discord_id_from_local_index)

### Description
Gets a Discord ID corresponding to the network player with `localIndex`

### Lua Example
`local stringValue = network_discord_id_from_local_index(localIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| localIndex | `integer` |

### Returns
- `string`

### C Prototype
`const char* network_discord_id_from_local_index(u8 localIndex);`
