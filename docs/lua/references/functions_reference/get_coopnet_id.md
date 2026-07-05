
## [get_coopnet_id](#get_coopnet_id)

### Description
Gets the CoopNet ID of a player with `localIndex` if CoopNet is being used and the player is connected, otherwise "-1" is returned

### Lua Example
`local stringValue = get_coopnet_id(localIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| localIndex | `integer` |

### Returns
- `string`

### C Prototype
`const char* get_coopnet_id(s8 localIndex);`
