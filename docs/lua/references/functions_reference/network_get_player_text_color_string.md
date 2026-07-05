
## [network_get_player_text_color_string](#network_get_player_text_color_string)

### Description
Gets the DJUI hex color code string for the player corresponding to `localIndex`'s cap color

### Lua Example
`local stringValue = network_get_player_text_color_string(localIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| localIndex | `integer` |

### Returns
- `string`

### C Prototype
`const char* network_get_player_text_color_string(u8 localIndex);`
