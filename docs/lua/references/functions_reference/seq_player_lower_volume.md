
## [seq_player_lower_volume](#seq_player_lower_volume)

### Description
Fades the volume of `player` to `percentage` over `fadeDuration`

### Lua Example
`seq_player_lower_volume(player, fadeDuration, percentage)`

### Parameters
| Field | Type |
| ----- | ---- |
| player | `integer` |
| fadeDuration | `integer` |
| percentage | `integer` |

### Returns
- None

### C Prototype
`void seq_player_lower_volume(u8 player, u16 fadeDuration, u8 percentage);`
